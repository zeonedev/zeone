
Debian
====================
This directory contains files used to package zeoned/zeone-qt
for Debian-based Linux systems. If you compile zeoned/zeone-qt yourself, there are some useful files here.

## zeone: URI support ##


zeone-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zeone-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zeone-qt binary to `/usr/bin`
and the `../../share/pixmaps/zeone128.png` to `/usr/share/pixmaps`

zeone-qt.protocol (KDE)

