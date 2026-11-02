# 🚀 TFDrive All-In-One Toolkit (Google Colab)

Aplikasi pengunduh serbaguna langsung ke **Google Drive** pribadi Anda via Google Colab tanpa kuota internet lokal dan tanpa memakan kapasitas hard disk PC.

---

## ✨ 4 Fitur Utama yang Ditambahkan:

### 1. 📥 Batch & Multi-Link Downloader
- Bisa memasukkan **banyak link sekaligus** (satu link per baris) untuk mengunduh banyak part file otomatis (misal: `part1.rar`, `part2.rar`, dst.).
- Pilihan mode: **Single (Aman - wget)** untuk FuckingFast/MediaFire, atau **Multi-Connection (aria2c 16x)** untuk direct link.

### 2. 🧲 Torrent & Magnet Downloader
- Unduh langsung dari link **Magnet** atau upload file **`.torrent`**.
- Kecepatan tinggi menggunakan jaringan peer Google Colab.

### 3. 🗜️ Auto-Extract (RAR, ZIP, 7z, Multi-part)
- Ekstrak arsip langsung di dalam Google Drive tanpa perlu mengunduh file ke PC terlebih dahulu.
- Mendukung password dan opsi otomatis hapus arsip asli setelah ekstrak untuk menghemat ruang Drive.

### 4. 📹 Video & Audio Downloader (yt-dlp)
- Unduh video dari YouTube, TikTok, Instagram, Twitter/X, Facebook, dll.
- Pilihan format: **Video Kualitas Terbaik (MP4/MKV)** atau **Audio Saja (MP3)**.

---

## 🛠️ Cara Penggunaan
1. Buka [Google Colab](https://colab.research.google.com).
2. Upload file [`TFDrive_Colab.ipynb`](./TFDrive_Colab.ipynb).
3. Jalankan **Langkah 1 (Mount Google Drive)** sekali saja.
4. Pilih dan jalankan fitur yang Anda butuhkan (Fitur 1, 2, 3, atau 4). Semua hasil otomatis tersimpan di folder Google Drive Anda: **`TFDrive_Downloads`**.
