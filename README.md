# Asus UEFI BIOS Settings ![BIOS Version: 1903](https://img.shields.io/badge/BIOS-1903-red) ![Motherboard: Z390-E](https://img.shields.io/badge/MB-Z390--E-green)

### ⚠️ PLEASE READ FIRST ⚠️

The UEFI BIOS settings for the motherboard I have used for this may be different than some others. If you would like me to include a setting haven't included, correct any false information, or update this readme to a newer BIOS version, please submit a new issue. Also, your BIOS version may not be updated or may be newer than this readme was last made for, please check the BIOS version by the title to your own. Here's how:

- Make sure your on the "Main" tab/menu
- Right at the top, under "BIOS Information," there should be your BIOS Version

This is a fully-fledged readme with a list of all Asus ROG UEFI BIOS settings and their purpose. As always, the BIOS version this readme was last updated for will be at the top so check what version you have before reading this just so you don't get confused.

As you might notice, the table of contents includes every tab/menu, even those that don't have settings in them. This is meant to be a bit of a guide, so all the options on these extra tab/menu will be listed with their purpose as well.

(If I ever fall behind and don't seem to be responding to issues, you are welcome to fork this and update it so people can continue using it)
### 📕 Contents

- [❤️ My Favorites](#-my-favorites)
- [⚙️ Main](#%EF%B8%8F-main)
- [🔧 Ai/Extreme Tweaker](#-ai-extreme-tweaker)
- [🛠 Advanced](#-advanced)
- [📺 Monitor](#-monitor)
- [⏫ Boot](#-boot)
- [🧰 Tool](#-tool)
- [❌ Exit](#-exit)

## ❤️ My Favorites

Pretty self explanatory, you can favorite certain settings and they will show up here for quick & easy access.

## ⚙️ Main

### Bios Information

**BIOS Version:** The version of your BIOS

**Build Date and Time:** The date the BIOS was compiled

**EC Version:** The Embedded Controller firmware version. The Embedded Controller is a chip that handles multiple functions such as keyboard input or power on after power loss

**LED EC1 Version:**  The Asus Aura chip firmware version. Used for controlling RGB headers

**LED EC2 Version:** The Asus Aura chip firmware version. Used for controlling RGB headers (supposidly the 2nd chip on the board)

**ME FW Version:** Exclusively for Intel Boards. The firmware version for the Intel Management Engine, which is a parallel operating system running on an isolated chip, but with access to your PC’s hardware that performs various tasks. Some people have called it hardware-level spyware. Learn more: https://www.youtube.com/watch?v=Lr-9aCMUXzI

**PCH Stepping:** Unknown

### Processor Information

**Brand String:** Your CPU brand, generational information, and base core clock

**CPU Speed:** The current core clock your CPU is running at

**Total Memory:** The total amount of DRAM installed in your system

**Memory Frequency:** The frequency your DRAM is running at

### Settings

**System Language:** The language your system is set to, will affect the language the BIOS is displayed in and the default selection for your OS on first setup

**System Date:** The current date the system is set to, should be the current day

**System Time:** The current time the system is set to, should be the current time

**Access Level:** The current access level in the BIOS. User means access to the BIOS screen, but none of the settings can be changed. Administrator means you have all permissions. You can set passwords for both User and Administrator, if you have one for User it will need to be entered before you see the BIOS screen

#### Security

**Administrator Password:** The password needed for Administrator level access

**User Password:** The password needed before the BIOS screen is seen, required to fully boot

### 🔧 Ai/Extreme Tweaker

**Target CPU Turbo-Mode Frequency:** This is the frequency your CPU will attempt to ramp up to when it is being used heavily, as in the name, it "turbos" up when under high load

**Target CPU @ AVX Frequency:** Advanced Vector Extensions is a type of calculation/instruction method thats very fast, unfortunately, it commonly creates too much load on CPU and overheats it. This is the target frequency the CPU will attempt to go to when under an AVX load

**Target DRAM Frequency:** The frequency your DRAM is attempting to run at

**Target Cache Frequency:** The frequency your L1, L2, and L3 cache are attempting to run at

**Ai Overclock Tuner:** 
