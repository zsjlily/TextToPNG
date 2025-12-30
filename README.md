# TextToPNG
A simple app to turn inputted text into an image block with coloured background, which can then be copied to notion work space. 

# TextToPNG

**TextToPNG** is a lightweight macOS desktop app for turning free-form text into clean PNG images.

It’s designed for fast visual text generation: slides, posters, labels, diagrams, social graphics, and anywhere you need styled text without opening a full design tool.

## Features

- Free-text input (multi-line supported)
- Aspect ratios:
  - Square (1:1)
  - 3:1
  - 10:1
  - 20:1
- Text alignment:
  - Left
  - Center
  - Right
- Font families:
  - Default (sans-serif)
  - Serif
  - Monospace
- Font styles:
  - Bold
  - Italic
  - Underline
- Adjustable font size (slider)
- Custom text and background colors
- Live preview before copying
- One-click copy to clipboard as a PNG

No internet connection. No tracking. Everything runs locally.

---

## How to Use

1. Launch the app
2. Paste or type your text
3. Choose layout, font, and colors
4. Click **Generate PNG**
5. Review the preview
6. Click **Copy to Clipboard**
7. Paste anywhere that accepts images

The generated PNG is also saved locally for reuse.

---

## Installation (macOS)

Download the latest release from the **Releases** page.

On first launch, macOS may warn that the app is from an unidentified developer:

1. Right-click the app
2. Select **Open**
3. Click **Open** again

This is a standard macOS security prompt for unsigned apps.

---

## Built With

- Python 3
- Tkinter (GUI)
- Pillow (image rendering)
- PyInstaller (macOS app packaging)

---

## Privacy

TextToPNG runs entirely on your machine.
No data is collected, stored remotely, or transmitted.

---

## License

MIT License — free to use, modify, and distribute.
