# Hp-G4-Opencore-EFI-Sonoma

This repository contains a generic OpenCore based EFI folder for booting macOS on HP EliteDesk 800 G4 Mini computers.

This EFI is based off the excellent work of deeveedee over at insanelymac.

For more information on how to install macOS on a HP EliteDesk 800 G4 Mini please consult the linked thread above.

For convenience sake this repository includes the recommended UEFI configuration and additional DeviceProperties configurations in the EXTRAS folder.

## Features of this EFI:

Smbios is based on a macmini 8,1

Working macOS boot
Graphical boot picker via OpenCanopy with BigSurFlat theme
Usb Ports
Graphics 
Sound both output through HDMI and sounc in for Mic
Graphics aceleration 
Monteray 
Big Sur
Ventura 
Sonmoa with side car and extra fetures 

Everything works just like a mac mini 

## Please Generate your own serials though OCAT or somthing similer


## Specs
Intel i3 6th Gen T @ (35w) 2-core/4-thread
16GB DDR4 1600MHz
6 x USB 3, 2 front, 4 back
2.5" SSD Samsung 860 EVO 500GB
BCM94352HMB(Mini PCI) wifi/bt card
65w external power supply
OpenCore 0.9.2


## Specs
|:---|:---|
| Computer Model | ThinkPad E480 (2018) |
| CPU | Intel Core i7-8550U |
| Memory | DDR4 2400 Mhz. Manually upgrade to 2x16 GB |
| NVMe SSD | Manually change to Lenovo SL700 M.2 512 GB |
| SATA SSD | Manually change to Toshiba TR200 SATA 512 GB |
| Integrated Graphics | Intel UHD Graphics 620 |
| Discrete Graphics | Radeon (TM) RX 550 (2 GB) |
| Ethernet | RTL8168/8111/8112 Gigabit Ethernet Controller |
| Sound Card | Conexant CX20753/4 (layout-id: 15) |
| Wireless Card | Manually change to BCM94352Z (DM1560) |



Security -> Secure Boot -> Disable
Advanced -> CPU Setup -> VTd -> Disabled
Devices -> Video Setup -> Active Video -> IGD
Devices -> Video Setup -> Pre-Allocated Memory Size -> 64MB Min or set to 1024 like I have 
Devices -> Video Setup -> Total Graphics Memory -> Maximum
USB port mapping
I have enclosed the USBports.kext derived from hackintool. It should work on your PC of this model.

If you can Support My work 

[I'm an inline-style link] www.paypal.com/stsbarrow