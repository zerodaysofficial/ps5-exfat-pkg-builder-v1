# PS5 exFAT to PKG Builder

A Windows GUI tool for converting PS5 exFAT disk images into PKG packages.

The application provides a simple workflow for mounting an exFAT image, copying its contents, building the PKG and verifying the final package.

---

## Features

- Convert `.exfat` images to `.pkg`
- Simple graphical user interface
- Automatic exFAT image mounting
- PKG creation using LibProsperoPKG
- Selectable firmware / SDK preset
- Support for custom SDK values
- User-selectable output PKG path
- User-selectable temporary working folder
- Optional SHA-256 verification of copied files
- Detailed conversion logs
- Conversion progress display
- Integrated PKG Builder
- Original exFAT image is not modified

---

## Conversion Workflow

```text
exFAT image
     ↓
Mount image
     ↓
Copy files
     ↓
Build PKG
     ↓
Verify package
