# Website LandPrep — SOP Persiapan Lahan

Website statis responsif untuk menampilkan 15 SOP Land Preparation.

## Cara membuka
- Untuk pengujian, jalankan server lokal dari folder ini, misalnya `python -m http.server 8000`, lalu buka `http://localhost:8000`.
- Untuk penggunaan publik, unggah seluruh isi folder `website` ke layanan hosting statis seperti GitHub Pages, Netlify, atau Cloudflare Pages.
- Jangan hanya mengunggah `index.html`; sertakan folder `assets`, `data`, dan `documents`.

## Struktur
- `index.html` — halaman utama.
- `assets/style.css` — tampilan dan responsif.
- `assets/app.js` — pencarian, filter, dan tampilan detail SOP.
- `data/sop_data.json` — sumber data 15 SOP.
- `data/sop_index.csv` — indeks SOP.
- `documents/Kumpulan_SOP_Land_Preparation_15_SOP.docx` — dokumen Word.

## Fitur
- Beranda dan ringkasan materi.
- Daftar SOP berdasarkan lima cabang.
- Pencarian dan filter cabang.
- Detail SOP, termasuk prosedur, K3, lingkungan, rekaman, dan catatan teknis.
- Unduhan dokumen Word, CSV, dan JSON.
- Tampilan responsif untuk desktop dan ponsel.

## Catatan
Materi SOP adalah draf akademik/template berdasarkan diagram sumber. Parameter teknis harus ditinjau dan disahkan oleh perusahaan/tenaga kompeten sebelum penggunaan operasional.
