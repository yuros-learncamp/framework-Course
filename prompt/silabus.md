# Kursus PostgreSQL untuk Pemula
**15 Pertemuan × 5 Modul = 75 Modul**

Dataset utama yang digunakan: *Sistem Perpustakaan Digital* (`buku`, `anggota`, `peminjaman`).

---

## Pertemuan 1 — Mengenal Data & Database
1. Apa itu data? (analogi catatan sehari-hari).  
2. Mengapa kita butuh database.  
3. DBMS vs file biasa.  
4. Pengenalan PostgreSQL dan sejarah singkatnya.  
5. Potensi Penggunaan Database  

## Pertemuan 2 — Struktur Database
6. Konsep database, skema, tabel, baris, kolom.  
7. Tipe data sederhana (numeric, varchar, date).  
8. Membuat database dengan `CREATE DATABASE`.  
9. Membuat tabel sederhana dengan `CREATE TABLE`.  
10. Praktik: tabel `buku` pertama.  

## Pertemuan 3 — Mengisi dan Mengelola Data
11. Menambahkan data dengan `INSERT`.  
12. Menampilkan isi tabel dengan `SELECT *`.  
13. Mengubah data dengan `UPDATE`.  
14. Menghapus data dengan `DELETE`.  
15. Praktik: isi data contoh ke tabel `buku`.  

## Pertemuan 4 — Mencari Data
16. Menampilkan kolom tertentu.  
17. Menyaring data dengan `WHERE`.  
18. Operator perbandingan (=, >, <, LIKE/ILIKE).  
19. Mengurutkan data dengan `ORDER BY`.  
20. Praktik: mencari buku berdasarkan penulis.  

## Pertemuan 5 — Hubungan Antar Tabel
21. Membuat tabel `anggota`.  
22. Membuat tabel `peminjaman`.  
23. Konsep Primary Key.  
24. Konsep Foreign Key.  
25. Praktik: hubungkan `anggota` dan `peminjaman`.  

## Pertemuan 6 — JOIN Dasar
26. INNER JOIN (menggabungkan data 2 tabel).  
27. LEFT JOIN (data meski tidak lengkap).  
28. RIGHT JOIN (contoh sederhana).  
29. Praktik query pinjaman buku per anggota.  
30. Latihan mandiri: laporan gabungan.  

## Pertemuan 7 — Ringkasan Data
31. Fungsi COUNT untuk menghitung data.  
32. Fungsi SUM, AVG, MIN, MAX.  
33. GROUP BY sederhana.  
34. HAVING vs WHERE.  
35. Praktik: laporan jumlah pinjaman per anggota.  

## Pertemuan 8 — Desain Database yang Baik
36. Masalah duplikasi data.  
37. Normalisasi pengantar.  
38. Bentuk normal pertama (1NF).  
39. Bentuk normal kedua (2NF).  
40. Praktik: memperbaiki tabel perpustakaan.  

## Pertemuan 9 — Fitur Tambahan SQL
41. Fungsi string (UPPER, LOWER, CONCAT atau operator ||).  
42. Fungsi tanggal (NOW, EXTRACT, TO_CHAR).  
43. Fungsi kondisi (CASE, COALESCE).  
44. Praktik: laporan pinjaman bulan tertentu.  
45. Latihan mandiri: laporan keterlambatan.  

## Pertemuan 10 — View (Tabel Virtual)
46. Apa itu View.  
47. Membuat View sederhana.  
48. Menggunakan View untuk laporan.  
49. Kapan menggunakan View.  
50. Praktik: View laporan pinjaman per bulan.  

## Pertemuan 11 — Keamanan Sederhana
51. Membuat role/user baru.  
52. Memberi izin SELECT (GRANT) ke role tertentu.  
53. Memberi izin penuh ke role superuser/admin.  
54. Simulasi login dengan role berbeda.  
55. Praktik: role `admin` dan `anggota`.  

## Pertemuan 12 — Backup & Restore
56. Mengapa backup penting.  
57. Backup dengan `pg_dump`.  
58. Restore database menggunakan `psql` atau `pg_restore`.  
59. Praktik: backup database perpustakaan.  
60. Latihan: simulasikan kehilangan data lalu restore.  

## Pertemuan 13 — Sedikit Tentang Performa
61. Apa itu index (analogi daftar isi buku).  
62. Membuat index sederhana.  
63. Melihat rencana query dan pengaruh index dengan `EXPLAIN`.  
64. Praktik: query dengan dan tanpa index.  
65. Latihan: tambahkan index ke kolom judul.  

## Pertemuan 14 — Otomatisasi Sederhana
66. Apa itu Fungsi & Prosedur di Postgres (PL/pgSQL).  
67. Membuat fungsi/prosedur sederhana.  
68. Konsep Trigger dan Trigger Function di PostgreSQL.  
69. Praktik: trigger untuk update stok buku otomatis.  
70. Latihan: fungsi laporan harian.  

## Pertemuan 15 — Proyek Mini & Refleksi
71. Merancang database perpustakaan mini (final).  
72. Mengisi data minimal 50 baris.  
73. Membuat laporan pinjaman bulanan.  
74. Membuat role admin & anggota dengan izin berbeda.  
75. Refleksi: apa yang sudah dipelajari dan arah lanjutan (intermediate).  
"""
