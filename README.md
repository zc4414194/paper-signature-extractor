# ✍️ Paper Signature Extractor

> **Free, open-source, 100% client-side web tool to extract crisp, transparent PNG signatures and notary seals from paper photos.**  
> Zero server uploads · Pure HTML5 Canvas · Uncompromising privacy.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Pure Client-Side](https://img.shields.io/badge/Architecture-100%25%20Client--Side-brightgreen.svg)]()
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-orange.svg)]()
[![Powered by Dopic](https://img.shields.io/badge/Powered%20by-Dopic.app-6366f1.svg)](https://dopic.app)

---

## 🌐 Live Demo

👉 **Try it directly online:**  
**[https://your-github-username.github.io/paper-signature-extractor/](https://your-github-username.github.io/paper-signature-extractor/)**

*(Replace `your-github-username` with your own GitHub handle once deployed via GitHub Pages)*

---

## 💡 The Problem

Signing digital contracts (PDFs, Word docs, Google Docs, invoices) often requires a transparent PNG signature.  
However, when you snap a photo of your signature written on paper with your phone:
- The paper looks gray, yellowish, or shadowed.
- Standard background removal tools blur the fine ink strokes or charge high monthly subscription fees.
- Uploading personal handwritten signatures or official company seals to third-party cloud servers poses **severe privacy and identity theft risks**.

**Paper Signature Extractor** solves this completely by processing every single pixel locally in your browser using HTML5 Canvas.

---

## ✨ Features

- **⚡ Instant Paper Shadow Removal:** Dynamic luminosity thresholding eliminates uneven paper lighting and shadows while preserving delicate pen strokes.
- **🎨 Ink Color Customization:** Instantly switch between Original Ink, Crisp Dark Black (`#0f172a`), Royal Navy Blue (`#1e40af`), Notary Red Stamp (`#dc2626`), or Emerald Green.
- **🔴 Dual Mode: Signature & Wax/Notary Seal:** Custom color-separation heuristics automatically extract red notary seals and company stamps without losing color vibrance.
- **✂️ Auto-Trim Margins:** Automatically crops away empty transparent space around the signature for tight placement in documents.
- **🧹 Precision Touch-up Eraser:** Erase unwanted paper specks, stray marks, or lined notebook rules with an interactive eraser brush and Undo support.
- **📋 One-Click Copy to Clipboard:** Copy the transparent PNG directly into your OS clipboard to paste into Word, WPS, or Photoshop without saving a file first.
- **🔒 100% Offline & Private:** Zero server-side code, zero APIs, zero tracking. Disconnect your internet and it still works flawlessly.

---

## 🚀 Quick Start (Run Locally)

No Node.js, npm, or build step required!

1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-github-username/paper-signature-extractor.git
   cd paper-signature-extractor
   ```
2. Double-click `index.html` to open it in any modern browser (Chrome, Edge, Safari, Firefox).
3. That's it!

---

## 📦 How to Deploy on GitHub Pages (Free Hosting)

Deploy your own live version in less than 60 seconds:

1. Create a new public repository on GitHub (e.g., `paper-signature-extractor`).
2. Push `index.html` and `README.md` to the `main` branch.
3. Go to **Settings** → **Pages** in your repository.
4. Under **Branch**, select `main` and root `/`, then click **Save**.
5. Your tool is now live at `https://<your-username>.github.io/paper-signature-extractor/`!

---

## 🛠️ Related Tools & Sponsorship

This open-source project is proudly sponsored and maintained by **[Dopic](https://dopic.app)**.

Looking for more free creative tools?
- 🛂 **[AI Passport Photo Maker](https://dopic.app)** — Create biometric compliant passport and visa photos for 150+ countries.
- ✂️ **[AI Background Remover](https://dopic.app)** — Remove complex backgrounds with high-resolution edge detection.
- 🗜️ **[Batch Image Compressor & Converter](https://dopic.app)** — Lossless compression right in your browser.

---

## 📄 License

This project is licensed under the **MIT License** — you are free to use, modify, and distribute it for personal or commercial projects. See the [LICENSE](LICENSE) file for details.

