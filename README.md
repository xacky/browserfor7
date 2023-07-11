# browserfor7
Unofficial build of Firefox recompiled to work on Windows 7 and 8.x

Proof of concept for now, designed for those who are unwilling or unable to upgrade to Windows 10/11.
Latest VCredist required to install.

To build, download the Firefox 116 beta3 source code at http://archive.mozilla.org/pub/firefox/releases/116.0b3/source/firefox-116.0b3.source.tar.xz, then reverse the installer patch to restore Windows 7/8 compatibility, then compile as normal, then use ./mach package to build an installer.

Not affiliated with  Mozilla, use at own risk, no tech support provided. Uses "Nightly" branding.
