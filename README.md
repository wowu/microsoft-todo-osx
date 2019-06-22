## ⚠️ Microsoft has finally launched the MacOS version, you can download it from Mac App Store [here](https://apps.apple.com/app/microsoft-to-do/id1274495053?mt=12&utm_source=Direct). Thanks everyone for using this wrapper 🙌

---

# Microsoft To-Do app for MacOS

As Microsoft plans to shut down Wunderlist and there is no Microsoft To-Do app for MacOS yet, I've created one using [nativefier](https://github.com/gfpacheco/Nativefier).

[Download app (44MB)](https://github.com/Wowu/microsoft-todo-osx/raw/master/To-Do.zip)

![Screenshot](https://github.com/Wowu/microsoft-todo-osx/raw/master/screenshot.png)


## Nativefier

I used the following command:

```bash
$ nativefier --name "To-Do" -p "OSX" --counter -i ./To-Do --single-instance --width=880 --height=630 --min-width=600 --min-height=330 --internal-urls="((microsoftonline|live)\.com|(todo|to-do)\.microsoft\.com)" --disable-context-menu --inject ./style.css https://to-do.microsoft.com/login
```

## Features

- [x] Context menu
- [x] Native notifications w/ counter
- [x] Hide "Get the app" button
