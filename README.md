# Simulator Cost per BCM

Aplikasi web untuk menghitung **Cost per BCM** (loading, hauling, dozing) per kombinasi fleet loader × hauler × material × jarak, beserta revenue dan margin.

**Buka aplikasi:** https://wiraramadana74-rgb.github.io/simulator-cost-bcm/

## Cara pakai
1. Buka aplikasi, masuk ke menu **Data & Parameter**.
2. Impor file Excel raw data (format seperti *Simulasi Cost per BCM.xlsx*, dengan sheet: POP Unit, P_FC, P_OW, Cost Act by Unit, P_MP, Match Factor Pdty, Simulasi).
3. Atur skenario di menu **Simulasi**, lihat hasil di **Ringkasan** dan **Analisa Jarak**.
4. Jika raw data berubah, impor ulang file Excel-nya.

## Tentang data
- Repository ini **hanya berisi aplikasinya**. Tidak ada data biaya di sini.
- File Excel dibaca langsung di browser dan **tidak dikirim ke server mana pun**.
- Data tersimpan di browser masing-masing pengguna. Gunakan tombol *Simpan backup* / *Pulihkan dari backup* untuk memindahkan data.
- Jangan upload file Excel atau file backup (.json) ke repository ini.
