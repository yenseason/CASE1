# Dashboard Visualisasi Data Penjualan — CASE1

## Identitas Mahasiswa

| Keterangan | Informasi |
|---|---|
| Nama | Neysalva Calista Firlin |
| NPM | 241051005 |
| Mata Kuliah | Visualisasi Data |
| Program Studi | Sistem Informasi |

## 1. Deskripsi Proyek

CASE1 merupakan proyek visualisasi data yang berfokus pada analisis data transaksi penjualan dan performa produk. Proyek ini dikembangkan menggunakan Python dengan memanfaatkan Streamlit sebagai framework untuk membangun dashboard interaktif.

Dashboard ini diberi judul **Laporan Operasional Penjualan — Bedah Kasus 1: Visualisasi Data Transaksi & Performa Barang**. Dashboard menyajikan informasi mengenai aktivitas penjualan melalui ringkasan data, grafik tren pendapatan, serta perbandingan kontribusi pendapatan berdasarkan kategori produk.

Hasil pengolahan data disajikan dalam bentuk visualisasi agar informasi penjualan lebih mudah dipahami dan dapat digunakan sebagai bahan evaluasi.

## 2. Latar Belakang

Data transaksi penjualan merupakan salah satu sumber informasi penting untuk mengetahui perkembangan aktivitas bisnis. Namun, data dalam jumlah besar akan lebih sulit dipahami apabila hanya disajikan dalam bentuk tabel atau angka.

Oleh karena itu, diperlukan proses visualisasi data untuk mengubah data transaksi menjadi informasi yang lebih terstruktur, informatif, dan mudah dianalisis.

Melalui proyek CASE1, data penjualan diolah dan ditampilkan dalam dashboard interaktif agar pengguna dapat mengamati tren pendapatan, memahami kontribusi kategori produk, serta memperoleh gambaran mengenai performa penjualan.

## 3. Tujuan Proyek

- Mengolah dan menganalisis data transaksi penjualan menggunakan Python.
- Menyajikan data penjualan dalam bentuk grafik dan informasi visual.
- Mengetahui perkembangan pendapatan berdasarkan waktu.
- Mengidentifikasi kontribusi pendapatan dari setiap kategori produk.
- Menampilkan ringkasan transaksi dan performa produk melalui dashboard interaktif.
- Mempermudah proses pemahaman dan evaluasi informasi penjualan.

## 4. Visualisasi yang Digunakan

Visualisasi pada dashboard CASE1 meliputi:

1. **Tren Pendapatan Harian**  
   Menampilkan perubahan pendapatan berdasarkan tanggal transaksi untuk mengetahui perkembangan pendapatan dari waktu ke waktu.

2. **Proporsi Pendapatan per Kategori**  
   Menampilkan perbandingan kontribusi pendapatan dari setiap kategori produk sehingga kategori dengan kontribusi terbesar dapat diamati.

3. **Kartu Ringkasan Statistik (Summary Cards)**  
   Menyajikan informasi utama berupa total transaksi, total pendapatan, jumlah unit terjual, rata-rata nilai transaksi, dan produk terlaris.

## 5. Fitur Dashboard

Dashboard CASE1 memiliki beberapa fitur utama, yaitu:

- **Ringkasan Penjualan:** Menampilkan informasi statistik utama mengenai aktivitas penjualan.
- **Filter Kategori Produk:** Memungkinkan pengguna memilih kategori produk tertentu.
- **Filter Produk:** Memungkinkan pengguna menampilkan informasi berdasarkan produk yang dipilih.
- **Filter Rentang Tanggal:** Memudahkan pengguna melihat data penjualan berdasarkan periode waktu tertentu.
- **Visualisasi Tren Pendapatan:** Menampilkan perubahan pendapatan harian.
- **Analisis Kategori Produk:** Menampilkan proporsi pendapatan berdasarkan kategori produk.
- **Dashboard Interaktif:** Menyediakan tampilan informasi yang dapat disesuaikan melalui filter.

## 6. Hasil Analisis Awal

Berdasarkan hasil pengolahan awal dataset penjualan, diperoleh beberapa informasi berikut:

- Jumlah transaksi tercatat sebanyak **1.000 transaksi**.
- Total pendapatan mencapai **Rp57.341.725.000**.
- Rata-rata nilai transaksi sebesar **Rp57.341.725**.
- Tren pendapatan harian menunjukkan adanya perubahan nilai pendapatan dari waktu ke waktu.

Hasil tersebut memberikan gambaran awal mengenai aktivitas penjualan. Visualisasi tren harian dan proporsi pendapatan per kategori dapat digunakan untuk mengamati pola serta kontribusi penjualan secara lebih mudah.

## 7. Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| Python | Bahasa pemrograman untuk pengolahan data dan pengembangan aplikasi |
| Jupyter Notebook | Lingkungan untuk melakukan analisis data |
| Pandas | Mengolah dan memanipulasi dataset |
| Streamlit | Membangun dashboard interaktif |
| Plotly | Membuat visualisasi data interaktif |
| Git | Mengelola versi proyek |
| GitHub | Menyimpan dan membagikan source code proyek |

## 8. Live Dashboard

Dashboard CASE1 dapat diakses melalui Streamlit Community Cloud.

**Link Dashboard:** https://case1-visualisasi-penjualan-yenseason.streamlit.app/

## 9. Struktur Folder

```text
CASE1/
│
├── analisis_data.ipynb
├── app.py
├── dataset_penjualan.csv
├── requirements.txt
└── README.md
```

Keterangan:
- `analisis_data.ipynb` : File notebook untuk proses analisis dan pengolahan data.
- `app.py` : File utama untuk menjalankan aplikasi dashboard Streamlit.
- `dataset_penjualan.csv` : Dataset yang digunakan dalam analisis penjualan.
- `requirements.txt` : Daftar library Python yang diperlukan.
- `README.md` : Dokumentasi proyek.

## 10. Cara Menjalankan Secara Lokal

Untuk menjalankan dashboard CASE1 pada komputer lokal, ikuti langkah berikut:

**1. Clone repository GitHub**

```bash
git clone https://github.com/yenseason/CASE1.git
```

**2. Masuk ke direktori proyek**

```bash
cd CASE1
```

**3. Install seluruh library yang dibutuhkan**

```bash
pip install -r requirements.txt
```

**4. Jalankan aplikasi Streamlit**

```bash
streamlit run app.py
```

**5. Buka dashboard**

Setelah aplikasi berjalan, buka alamat lokal yang ditampilkan pada terminal, biasanya:

```text
http://localhost:8501
```

## 11. Repository GitHub

Source code dan seluruh file proyek CASE1 dapat diakses melalui repository berikut:

https://github.com/yenseason/CASE1
