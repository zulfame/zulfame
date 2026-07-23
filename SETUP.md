# 🖤 GitHub Profile README — Setup Guide

Ini adalah **profile README** monochrome (abu–hitam) yang animatif & interaktif.
Semua "animasi" di GitHub README berasal dari layanan SVG dinamis (typing, stats,
snake, waving header) — jadi tetap hidup langsung di halaman profilmu.

## 1. Aktifkan Profile README
1. Buat repo baru dengan **nama SAMA PERSIS dengan username GitHub-mu**
   (contoh: username `alex` → repo `alex`).
2. Centang **"Add a README file"** atau upload `README.md` ini.
3. Repo harus **public**. Selesai — profilmu langsung menampilkan README ini.

## 2. Ganti Placeholder
Cari & ganti di `README.md`:
| Placeholder            | Ganti dengan                          |
|------------------------|---------------------------------------|
| `yourusername`         | Username GitHub-mu                    |
| `Alex` / nama & bio    | Nama & deskripsi kamu                 |
| `you@example.com`      | Email kamu                            |
| link social / project  | URL asli milikmu                      |

## 3. Aktifkan Snake Animation (opsional tapi keren)
1. Salin folder `.github/workflows/snake.yml` ke repo profilmu.
2. Buka tab **Actions** di repo → jalankan workflow **"Generate Snake Animation"** sekali.
3. Workflow akan bikin branch `output` berisi SVG ular yang memakan grafik kontribusi.
   Setelah itu snake di README akan tampil otomatis & update tiap 12 jam.

## 4. Palet Warna (Monochrome)
Semua kartu memakai skema gelap konsisten:
- Background : `#0d0d0d`  (hampir hitam)
- Aksen terang : `#e5e5e5` (abu terang)
- Teks : `#9a9a9a` (abu)
- Ikon/garis : `#8b8b8b`
- Badge : gradasi `#000000 → #2b2b2b`

Ubah nilai hex pada parameter URL (`bg_color`, `text_color`, `color`, dll.)
kalau mau menyetel tingkat kegelapan.

## 5. Preview Lokal
Buka `README.md` di editor yang punya markdown preview (VS Code: `Ctrl/Cmd+Shift+V`),
atau langsung push ke GitHub untuk melihat semua animasi render penuh.
