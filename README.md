<h1 align="center">Cavasik</h1>
<div align="center">
    <img width="400" src="./assets/icons/io.github.TheWisker.Cavasik.png">
</div>
<p align="center">Audio visualizer based on CAVA</p>

<h2 align="center">Description</h2>

<p align="center">This is an audio visualizer based on <b>CAVA</b> with extended capabilities.</p>

<h2 align="center">Features</h2>

The visualizer features:

- Five **normal** drawing modes!
- Two **circle** drawing modes!
- Three **mirror** drawing modes!
- Four drawing **directions**!
- Customizable **LibAdwaita** interface!
- Set a single color or up to a 10 color linear gradient for **background** and **foreground**!
- Select different **foreground** colors for the mirrored images in **mirror** mode!
- Set up a **color animation** that changes the colors gradually in a loop!
- Configure *smoothing*, *noise reduction* and a few other **CAVA** settings!
- Change **background** and **foreground** colors through a **DBus interface**!

<h2 align="center">Screenshots</h2>

<div align="center">
    <img src="./assets/screenshots/main.png"></img>
</div>

<h3 align="center">Waves mode</h2>

<div align="center">
    <img src="./assets/screenshots/waves.png"></img>
</div>

<h3 align="center">Levels mode</h2>

<div align="center">
    <img src="./assets/screenshots/levels.png"></img>
</div>

<h3 align="center">Particles mode</h2>

<div align="center">
    <img src="./assets/screenshots/particles.png"></img>
</div>

<h3 align="center">Spine mode</h2>

<div align="center">
    <img src="./assets/screenshots/spine.png"></img>
</div>

<h3 align="center">Bars mode</h2>

<div align="center">
    <img src="./assets/screenshots/bars.png"></img>
</div>

<h3 align="center">Normal mirror + Waves mode</h2>

<div align="center">
    <img src="./assets/screenshots/mirror_normal.png"></img>
</div>

<h3 align="center">Inverted mirror + Waves mode</h2>

<div align="center">
    <img src="./assets/screenshots/mirror_inverted.png"></img>
</div>

<h3 align="center">Overlapping mirror + Waves mode</h2>

<div align="center">
    <img src="./assets/screenshots/mirror_overlapping.png"></img>
</div>

<h3 align="center">Direction top-bottom + Waves mode</h2>

<div align="center">
    <img src="./assets/screenshots/direction_top.png"></img>
</div>

<h3 align="center">Normal mirror + Direction left-right + Waves mode</h2>

<div align="center">
    <img src="./assets/screenshots/mirror_column.png"></img>
</div>

<h2 align="center">Installation</h2>

<h3>Flathub</h3>

You can install the **Cavasik** app from [Flathub][flathub] in its [app page][flathub-cavasik].

<a href="https://flathub.org/apps/details/io.github.TheWisker.Cavasik">
<img src="https://flathub.org/assets/badges/flathub-badge-en.png" height=48px/>
</a>

- For information on how to setup *flatpak* on any distro read [this][flatpak-setup].

<h3>Arch Linux</h3>

You can install **Cavasik** from the [AUR][aur] repository:

<a href="https://aur.archlinux.org/packages/cavasik">
<img src="https://camo.githubusercontent.com/f4b1ed57afad4fc0cc6f7acbfdf76be7bebaa104563e1e756ba7b91095eec461/68747470733a2f2f692e696d6775722e636f6d2f3958416a6330482e706e67" height=48px/>
</a>

- For information on how to install an [AUR][aur] package read [this][aur-wiki] wiki.

<h3>Manually</h3>

To manually install **Cavasik** start by **downloading** a [release][releases].
Then, **uncompress** the downloaded release into a resulting folder.
Make sure you have all the [dependencies][dependencies] needed.
Then, proceed to **run** the following commands:

```
#BUILD
arch-meson Cavasik build
meson compile -C build

#TEST
meson test -C build --print-errorlog

#INSTALL
meson install -C build
install -Dm644 Cavasik/LICENSE -t "/usr/share/licenses/cavasik"
```

<h2 align="center">Dependencies</h2>

<h3 align="left">Buildtime</h3>

The **Cavasik** application has the following *buildtime* dependencies:

- [meson][meson]

<h3 align="left">Runtime</h3>

The **Cavasik** application has the following *runtime* dependencies:

- [cava][cava]
- [libadwaita][libadwaita]
- [python-gobject][python-gobject]
- [python-cairo][python-cairo]
- [python-pydbus][python-pydbus]

<h2 align="center">Contributions</h2>

First and foremost, all contributions are welcome!
The **steps** involved when making a contribution are **explained** in the [CONTRIBUTING.md][contributing] file.
We look forward to your contributions!

- The **contributors** are located [here][contributors].

<h2 align="center">Translations</h2>

Secondly, all translations are also welcome!
The **steps** involved when making a translation are **explained** in the [CONTRIBUTING.md][contributing] file.
More **specific steps** can be found in the [CONTRIBUTING.md][lang-contributing] file in the `/lang` folder.
We look forward to your translations!

- The **credits** of the translators are located [here][translator-credits].

<h2 align="center">Code of Conduct</h2>

<p align="center"> This project follows the <a href="./.github/CODE_OF_CONDUCT.md"><b>Covenant Code of Conduct</b></a>.</p>

[flathub]: https://flathub.org/
[flathub-cavasik]: x
[flatpak-setup]: https://flatpak.org/setup/
[aur]: https://aur.archlinux.org/
[aur-wiki]: https://wiki.archlinux.org/title/Arch_User_Repository
[releases]: x
[dependencies]: x
[meson]: https://mesonbuild.com/
[cava]: x
[libadwaita]: x
[python-gobject]: x
[python-cairo]: x
[python-pydbus]: x
[contributors]: ./CONTRIBUTORS.md
[contributing]: ./CONTRIBUTING.md
[lang-contributing]: ./lang/CONTRIBUTING.md
[translator-credits]: ./lang/CREDITS.json

<h2 align="center">Forked</h2>
<div align="center">
    <img width="200" height="200" src="./assets/fork_profile.png"></img>
</div>
<h4 align="center">Fsobolev</h4>

<h2 align="center">Author</h2>
<div align="center">
    <img width="200" height="200" src="./assets/profile.png"></img>
</div>
<h4 align="center">TheWisker</h4>



**Cavasik** is an audio visualizer based on [CAVA](https://github.com/karlstav/cava) with customizable LibAdwaita interface.
* 4 drawing modes!
* Set single color or up to 10 colors gradient for background and foreground.
* Configure smoothing, noise reduction and a few other CAVA settings.
* Change background and foreground colors through a DBus interface.

![](https://raw.githubusercontent.com/TheWisker/cavasik/master/data/screenshots/main.png)

## DBus Interface

The application publishes the *io.github.TheWisker.Cavasik* DBus interface with the following methods:
- set_fg_colors(path: str) => bool: Sets the foreground colors sourcing them from the specified file
- set_bg_colors(path: str) => bool: Sets the background colors sourcing them from the specified file
Both methods return a booleand indicating the success of the operation.

The files must have the following format:
r,g,b
r,g,b,a 
10,10,10
10,10,10,0.1

This interface provides the ability to change colors dynamically from a bash file:

interface=io.github.TheWisker.Cavasik
object=/io/github/TheWisker/Cavasik
method=set_fg_colors
argument="~/colors-rgb"

dbus-send --session --dest=$interface --type=method_call --print-reply $object $interface.$method string:$argument

Thus, it can be integrated with tools like Pywal letting you change the colors of Cavasik dynamically to match the wallpaper.

## Building

The easiest way to build the development version of Cavasik is by using GNOME Builder as described [here](https://wiki.gnome.org/Newcomers/BuildProject).

## Translations

See [instruction](po/README.md) on how to translate the app to your language.

## Code of Conduct

This project follows the [GNOME Code of Conduct](https://wiki.gnome.org/Foundation/CodeOfConduct).
