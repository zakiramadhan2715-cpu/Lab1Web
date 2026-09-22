# Lab1Web — Praktikum 1: HTML Dasar

**Nama:** Owen
**NIM:** 312510463
**Mata Kuliah:** Pemrograman Web
**Universitas:** Universitas Pelita Bangsa

## Struktur Proyek

```
Lab1Web/
├── index.html
├── halaman2.html
├── images/
│   └── profil.jpg
└── README.md
```

## Penjelasan Langkah Praktikum

1. **Struktur Dasar HTML** — Membuat `index.html` dengan deklarasi `<!DOCTYPE html>`, elemen `<head>` berisi `<title>`, dan elemen `<body>` untuk konten.
2. **Membuat Paragraf** — Menambahkan dua paragraf menggunakan tag `<p>` untuk menjelaskan isi praktikum.
3. **Menambahkan Judul** — Menambahkan heading `<h1>` sebagai judul utama dan `<h2>` sebagai subjudul.
4. **Memformat Teks** — Mencoba tag pemformatan teks seperti `<b>`, `<i>`, `<strong>`, `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>`, dan `<sup>`.
5. **Menyisipkan Gambar** — Menyisipkan gambar profil menggunakan tag `<img>` dengan atribut `src`, `width`, `alt`, dan `title`, disimpan pada folder `images/`.
6. **Mengatur Ukuran Gambar** — Mengatur ukuran tampilan gambar dengan atribut `width`.
7. **Menambahkan Hyperlink** — Membuat `halaman2.html` dan menghubungkannya dengan `index.html` menggunakan tag `<a>` beserta hyperlink eksternal ke Google.
8. **Menambahkan List** — Membuat daftar keahlian dengan `<ul>` (unordered list) dan daftar target belajar dengan `<ol>` (ordered list).
9. **Menambahkan Komentar** — Menambahkan komentar `<!-- ... -->` sebagai penanda bagian kode.
10. **Menggabungkan Semua Elemen** — Menyusun seluruh elemen menjadi satu halaman profil mahasiswa yang utuh pada `index.html`.

*(Tempatkan screenshot hasil setiap tahap di sini sebelum dikumpulkan, misalnya dengan menambahkan gambar ke folder `screenshots/` dan menautkannya di bagian ini.)*

## Jawaban Pertanyaan

**1. Apa fungsi deklarasi `<!DOCTYPE html>` pada dokumen HTML?**
Deklarasi ini memberi tahu browser bahwa dokumen menggunakan standar HTML5, sehingga browser dapat merender halaman sesuai standar tersebut dan digunakan untuk validasi struktur dokumen.

**2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?**
Tag adalah penanda pembuka/penutup yang ditulis dengan kurung siku (contoh `<p>` dan `</p>`). Elemen adalah gabungan dari tag pembuka, isi, dan tag penutup (contoh `<p>Isi</p>`). Atribut adalah informasi tambahan yang ditulis di dalam tag pembuka (contoh `src` pada `<img src="foto.jpg">`).

**3. Apa perbedaan `<p>` dengan `<br>`? Jelaskan penggunaannya.**
`<p>` membuat sebuah paragraf baru dengan jarak (margin) sebelum dan sesudahnya, sedangkan `<br>` hanya memberikan pindah baris tanpa membuat paragraf baru maupun jarak tambahan.

**4. Apa fungsi atribut `href` pada tag `<a>`?**
Atribut `href` menentukan alamat tujuan (URL atau path file) yang akan dituju ketika link diklik.

**5. Apa perbedaan hyperlink ke halaman internal dengan hyperlink ke website eksternal?**
Hyperlink internal mengarah ke file/halaman lain dalam proyek yang sama (contoh `halaman2.html`), sedangkan hyperlink eksternal mengarah ke alamat website di luar proyek, biasanya berupa URL lengkap (contoh `https://www.google.com`).

**6. Apa fungsi atribut `src` dan `alt` pada tag `<img>`?**
`src` menentukan lokasi/path file gambar yang akan ditampilkan, sedangkan `alt` memberikan teks alternatif yang muncul jika gambar gagal dimuat dan membantu aksesibilitas (misalnya untuk pembaca layar).

**7. Apa perbedaan penggunaan `<ul>` dan `<ol>`?**
`<ul>` (unordered list) menampilkan daftar tanpa urutan/nomor, biasanya berupa bullet. `<ol>` (ordered list) menampilkan daftar berurutan dengan nomor, digunakan ketika urutan item penting.

**8. Apa yang terjadi jika path gambar pada atribut `src` salah?**
Gambar tidak akan tampil di browser (biasanya muncul ikon gambar rusak), dan sebagai gantinya browser menampilkan teks dari atribut `alt` jika tersedia.

**9. Mengapa struktur heading `h1` sampai `h6` perlu digunakan secara terstruktur?**
Struktur heading yang benar (dari `h1` sebagai judul utama hingga `h6` sebagai sub-sub judul) membantu pembaca dan mesin pencari memahami hierarki konten halaman, serta meningkatkan aksesibilitas dan SEO.

**10. Apa fungsi komentar `<!-- ... -->` dalam kode HTML?**
Komentar digunakan untuk memberi catatan/penjelasan pada kode tanpa ditampilkan di halaman web, dan juga dapat digunakan untuk menonaktifkan sementara bagian kode tertentu.

## Catatan

Praktikum ini difokuskan pada HTML Dasar. CSS dan JavaScript akan dipelajari pada pertemuan berikutnya sesuai RPS.
