<p align="center">
  <img src="assets/app-icon.png" width="128" height="128" alt="1xQuickConvertFormat app icon">
</p>

<h1 align="center">1xQuickConvertFormat</h1>

<p align="center">
  <strong>The fastest file converter for Mac: hold Shift, drag a file, drop it on a format.</strong><br>
  HEIC to JPG, MOV to MP4, Word to PDF, Excel to CSV, TCVN3/VNI to Unicode and 100+ more, offline, right from Finder.
</p>

<p align="center">
  <a href="https://github.com/xuanhieu/1xQuickConvertFormat/releases/latest"><strong>Download for macOS</strong></a> ·
  <a href="https://xuanhieu.org/1xquickconvertformat/">Website</a> ·
  <a href="README.vi.md">Tiếng Việt</a>
</p>

<p align="center">
  macOS 12.3+ · Apple Silicon and Intel · Signed and notarized by Apple
</p>

<p align="center"><img src="assets/hero-en.png" width="800" alt="The 1xQuickConvertFormat format wheel offering JPG, PNG, WebP, AVIF, TIFF, GIF and PDF for a HEIC photo"></p>

## Why 1xQuickConvertFormat

- **One gesture, no windows.** Hold <kbd>Shift</kbd> while dragging any file in Finder. A wheel appears under the cursor with only the formats that file can become. Drop it and the converted file is saved next to the original.
- **Private by design.** Every conversion runs on your Mac. Your files are never uploaded, and the app has no analytics or ads.
- **Built for real documents.** Office, PDF, video, audio, images, data and source code, including old Vietnamese documents typed in TCVN3 (.VnTime) or VNI fonts, converted to Unicode in one drop.
- **Lives in the menu bar.** Opens at login if you want and stays out of the Dock.

## What it converts

| Group | From | To |
|---|---|---|
| Images | PNG, JPG, WEBP, AVIF, HEIC/HEIF, TIFF, BMP, GIF, ICO, SVG | PNG, JPG, WEBP, AVIF, TIFF, BMP, GIF, ICO, PDF (from SVG) |
| Video | MP4, MOV, MKV, AVI, WEBM, WMV, FLV, 3GP, TS | MP4, MOV, MKV, AVI, WEBM, WMV, FLV, 3GP, TS, GIF |
| Audio | MP3, WAV, FLAC, AAC, M4A, OGG, OPUS, AIFF, WMA | the same, plus audio extracted from video |
| Documents | DOC, DOCX, RTF, ODT, Pages, WPS, EPUB, MHT, webarchive and more | PDF, DOCX, DOC, ODT, RTF, TXT, HTML, Markdown, EPUB |
| Spreadsheets | XLS, XLSX, XLSB, ODS, Numbers, CSV, TSV, DBF and more | PDF, XLSX, XLS, ODS, CSV, TSV, JSON, HTML |
| Presentations | PPT, PPTX, PPS, ODP, Keynote and more | PDF, PPTX, PPT, ODP |
| Text and code | TXT, Markdown, HTML, JS, TS, CSS, Python, SQL, PHP, Java, Go, Rust, C/C++, C#, Swift… | syntax-highlighted HTML, TXT, Markdown, PDF |
| Data | JSON, YAML, TOML, XML, CSV, TSV | JSON, YAML, TOML, XML, CSV, TSV |
| PDF | PDF | PNG, JPG, TXT |

Video and audio use [FFmpeg](https://ffmpeg.org) (`brew install ffmpeg`); layout-faithful Office conversions use [LibreOffice](https://www.libreoffice.org/download/). Both are free, installed separately and detected automatically. Formats that need a missing engine are shown dimmed with the reason.

## Plans

Every plan is for **one Mac**.

| | Free | Personal · 1 year | Personal · Lifetime |
|---|---|---|---|
| Price | free | 199.000đ or US$8.99 / year | 479.000đ or US$19.99 once |
| How to get it | an invite code from a friend, or join our Telegram channel | buy at [1x.xuanhieu.org](https://1x.xuanhieu.org/buy) | buy at [1x.xuanhieu.org](https://1x.xuanhieu.org/buy) |
| Images, text, data and code | ✓ | ✓ | ✓ |
| Video, audio, Office and PDF | | ✓ | ✓ |
| Many files at once | | ✓ | ✓ |
| Quality, size, output folder and codec options | | ✓ | ✓ |
| Move to a new Mac | | up to 3 times a year | up to 3 times a year |

New installs include a **7-day trial** of the Free features. Every activated Mac gets 3 invite codes to share. When 3 people you invite keep using the app for a week, you get 50% off Personal.

Pay by Vietnamese bank transfer (VietQR, also scannable with MoMo or ZaloPay) or by card or PayPal. The license key appears on screen and by email as soon as the payment arrives. Because of the free trial, purchases are not refundable (see [EULA §8](EULA.md#8-refunds)).

## Install

1. Download the latest `.dmg` from [Releases](https://github.com/xuanhieu/1xQuickConvertFormat/releases/latest) and check its SHA-256 against `SHA256SUMS.txt` if you like.
2. Open it and drag **1xQuickConvertFormat** into **Applications**.
3. Open the app, choose your language, and start the trial or enter your code in **Settings › License**.
4. Hold <kbd>Shift</kbd> while dragging a file in Finder.

To uninstall, quit the app from the menu bar and move it to the Trash.

## FAQ

**Is it really offline?** Conversions are. The app only goes online to activate and re-check your license about once a week, and it keeps working offline for 30 days between checks. See the [Privacy Policy](PRIVACY.md).

**Where do converted files go?** Next to the original, with a numbered name if a file with that name exists. Personal can choose another folder.

**Why Shift?** So ordinary drags in Finder are never interrupted. The wheel only appears when you hold Shift.

**Does it work on Intel Macs?** Yes. The app is universal (Apple Silicon and Intel) and needs macOS 12.3 or later.

**Can I move my license to a new Mac?** Yes. Use **Settings › License › Deactivate** on the old Mac, then enter the key on the new one (up to 3 times in 12 months).

## Support

Bugs and feature requests: [open an issue](https://github.com/xuanhieu/1xQuickConvertFormat/issues/new/choose). License and payment questions: mail@xuanhieu.org. Security reports: see [SECURITY.md](SECURITY.md).

## License

1xQuickConvertFormat is proprietary software. Copyright © 2026 Phạm Xuân Hiếu. All rights reserved. Use is governed by the [EULA](EULA.md) ([Tiếng Việt](EULA.vi.md)) and the [Privacy Policy](PRIVACY.md). This repository holds documentation and release downloads only; it contains no source code and grants no right to copy or modify the software.

The app builds on open-source components, including [Vertex](https://github.com/rainaku/Vertex) by rainaku (Apache License 2.0), [Tauri](https://tauri.app) and [Svelte](https://svelte.dev). Their notices are listed in the app under **About › Acknowledgements**.

---

Made in Vietnam by [Phạm Xuân Hiếu](https://xuanhieu.org).
