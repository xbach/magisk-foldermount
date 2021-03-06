# magisk-foldermount
Easily mount internal SD card folders to external SD folders.

Inspired by [FolderMount](https://forum.xda-developers.com/showthread.php?t=2192122) created by madmack, unfortunately his app does not work with MagiskSU.

### Disclaimer
This module does not guarantee functionality in any way, shape, or form. It is not my responsibility if this module does not work, breaks your SD card or eats your kittens. User discretion is advised.

## Usage
Open terminal then type:  
 `su`  
 `fmount -b [source] [destination]`

## Prerequisites
* Android 5.0+
* Magisk v13.1 or higher
* FAT32 formatted SD card (exFAT is known for causing problems, see #7)

## Links
* [Magisk](https://forum.xda-developers.com/apps/magisk/official-magisk-v7-universal-systemless-t3473445)
* [Support](https://forum.xda-developers.com/apps/magisk/module-magisk-foldermount-v0-8-t3591215)
* [GitHub](https://github.com/codebucketdev/magisk-foldermount)
* [Donate](https://www.paypal.me/codebucket/5)

## Changelog
v0.8
  - Initial release

v0.8.5
  - Small bugfixes and improvements
  - Added alternative way to mount folders on boot (post-fs-data.d support)

v0.8.7
  - Updated Magisk module template to v4
  - Fixed regex for lowercase UUIDs on some ROMs

v0.8.7.1
  - Added busybox binary back, Magisk v13 doesn't provide it's own anymore

v0.8.7.2
  - Reverted broken commits
