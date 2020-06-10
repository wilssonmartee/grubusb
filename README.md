# Multiboot USB

<https://mbusb.aguslr.com/>

## About

This is a project that contains a collection of [GRUB][] files and scripts that
will allow you to create a pendrive capable of booting [different ISO
files][isos].

![Demo
GIF](https://gitlab.com/aguslr/multibootusb/raw/master/docs/assets/img/demo.gif
"Demo")

## Usage
sh makeUSB.sh --efi /dev/sdb vfat 14G

/dev/sdb: usb name
efi: allow efi system
vfat: format
14G: partition space

## Documentation

Visit the [project's website for more information][website].


[grub]: https://www.gnu.org/software/grub/
[isos]: https://mbusb.aguslr.com/isos.html
[website]: https://mbusb.aguslr.com/
