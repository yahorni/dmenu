# [dmenu](https://github.com/NickoEgor/dmenu) - dynamic menu

[dmenu](https://dmenu.suckless.org/) with patches

## Patches
+ [border](https://tools.suckless.org/dmenu/patches/border/): adds border to dmenu window
+ [center](https://tools.suckless.org/dmenu/patches/center/): adds flag to open dmenu in floating center window
+ [fuzzymatch](https://tools.suckless.org/dmenu/patches/fuzzymatch/): fuzzy-matching in dmenu
+ [highlight](https://tools.suckless.org/dmenu/patches/highlight/): highlight searched text
+ [mousesupport](https://tools.suckless.org/dmenu/patches/mouse-support/): adds mouse support
+ [numbers](https://tools.suckless.org/dmenu/patches/numbers/): shows number of matches
+ [xresources](https://tools.suckless.org/dmenu/patches/xresources/): support for Xresources

## Additional bindings

+ `ctrl-shift-v` - paste clipboard
+ `ctrl-v` - paste primary selection

## Installation

Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

```
git clone https://github.com/NickoEgor/dmenu
cd dmenu
sudo make install
```
