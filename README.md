# ZXMapper
<p align="left">
  <img src="https://img.shields.io/github/license/rk797/zxmapper" alt="License">
  <img src="https://img.shields.io/github/stars/rk797/zxmapper" alt="Stars">
  <img src="https://img.shields.io/github/forks/rk797/zxmapper" alt="Forks">
  <img src="https://komarev.com/ghpvc/?username=zxmapper&label=Views" alt="Views">
</p>
ZXMapper is a C# application that allows you to remap your keystrokes to controller inputs using the Interception driver and ViGEmBus for virtual gamepad emulation.

## Features

- **Keystrokes to Controller Mapping**: Convert keyboard inputs to controller actions.
- **Interception Driver**: Capture and remap keyboard inputs.
- **Customizable Mappings**: Easily configure key-to-controller mappings.

## Installation

1. **Build the Project**:
    - Open the project in your preferred C# development environment (e.g., Visual Studio).
    - Restore the NuGet packages and build the solution.
2. Add Requirements to build dir
    - Add the ViGEmBus.msi file to the build dir
    - Add the interception.dll binary to the build dir
   

>[!NOTE]
> Please note that some antivirus programs may flag ZXMapper as a potential threat. This is a false positive. ZXMapper uses the Interception driver, which involves kernel-level communication to capture and remap keyboard inputs. Because of this, antivirus software might mistakenly identify it as malicious. To ensure ZXMapper functions correctly, you may need to temporarily disable your antivirus software during installation and use. Rest assured, ZXMapper is safe and does not pose any threat to your system.


## Credits

- **Interception Driver**: developers of the Interception driver. Learn more about Interception [here](https://github.com/oblitum/Interception).
- **ViGEmBus**: virtual gamepad emulation driver + wrapper. Learn more about ViGEmBus [here](https://vigem.org/projects/ViGEm/).

  
