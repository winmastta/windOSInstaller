# windOSInstaller

> The deployment wrapper and ISO tools for **windOS**.

![Banner](https://capsule-render.vercel.app/api?type=waving&color=0078D4&height=200&section=header&text=windOSInstaller&fontSize=70&animation=fadeIn&fontAlignY=35&desc=Deploy.%20Automate.%20Install.&descAlignY=55&descSize=20)

### 📋 Overview

**windOSInstaller** is the custom setup wrapper designed to streamline the installation of the windOS builds. It handles the deployment process, applies post-install configurations, and manages the user interface during the setup phase.

- **Parent Project:** [windOS](https://windos.nn1kk00.ru/)
- **Supported Builds:** windOS 10 LTSC, windOS 11
- **Status:** Stable

### 🛠️ Features

*   [x] **Custom UI:** A cleaner, faster alternative to the standard Windows OOBE.
*   [x] **Automation:** Automatically applies registry tweaks and drivers upon first boot.
*   [x] **ISO Integration:** Tools to repack modified WIM/ESD files into a bootable format.
*   [x] **Bypass Checks:** Includes patches for TPM 2.0 and Secure Boot requirements (for Win11).

### 📥 Building / Usage

To build a custom ISO using this installer:

1.  Clone this repository.
2.  Place your modified `install.wim` in the `source` folder.
3.  Run the builder script.

```bash
git clone https://github.com/winmastta/windOSInstaller.git
cd windOSInstaller
# Run the build script (check documentation for args)
.\build_iso.cmd
```

### 🏆 Credits

**Maintained by:**
*   [winmastt](https://github.com/winmastt)
*   [nn1kk00](https://github.com/nn1kk00)

---
*Visit the main website: [windos.nn1kk00.ru](https://windos.nn1kk00.ru/)*
