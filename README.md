# CV.Mulia-Globalindo-Sejahtera
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="CV. Mulia Globalindo Sejahtera - Penyedia bahan bangunan berkualitas di Malang.">
    <title>CV. Mulia Globalindo Sejahtera</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"> <!-- Menambahkan font Roboto -->
    <style>
        /* Reset CSS untuk menghilangkan margin dan padding default */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box; /* Mengatur box model */
        }

        /* Gaya untuk body */
        body {
            background: linear-gradient(to right, #007BFF, #FFFFFF); /* Latar belakang biru dan putih */
            font-family: 'Roboto', sans-serif; /* Menggunakan font Roboto */
        }

        /* Gaya untuk header */
        header {
            text-align: center; /* Menyelaraskan teks ke tengah */
            padding: 20px; /* Padding di dalam header */
        }

        /* Gaya untuk judul dengan gradiasi hitam dan putih */
        .gradient-text {
            background: linear-gradient(to right, #000000, #FFFFFF); /* Gradiasi hitam dan putih */
            -webkit-background-clip: text; /* Memotong latar belakang untuk teks */
            -webkit-text-fill-color: transparent; /* Mengisi warna teks dengan transparan */
            font-size: 2.5em; /* Ukuran font */
            margin: 0; /* Menghilangkan margin */
        }

        /* Garis pembatas di bawah header */
        .divider {
            height: 2px; /* Tinggi garis */
            background: #007BFF; /* Warna garis */
            margin: 20px 0; /* Margin atas dan bawah */
        }

        /* Gaya untuk kontainer utama */
        .container {
            display: flex; /* Menggunakan flexbox untuk layout */
            justify-content: space-between; /* Mengatur spasi antar elemen */
            padding: 20px; /* Padding di dalam kontainer */
        }

        /* Gaya untuk item dalam kontainer */
        .item {
            background: linear-gradient(to bottom right, #e0e0e0, #ffffff); /* Warna latar belakang item dengan gradiasi */
            padding: 15px; /* Padding di dalam item */
            margin: 10px; /* Margin antar item */
            flex: 1; /* Membuat item fleksibel */
            text-align: center; /* Menyelaraskan teks ke tengah */
            border-radius: 5px; /* Sudut melengkung */
        }

        /* Gaya untuk teks */
        .text {
            line-height: 1.5; /* Mengatur tinggi baris untuk teks */
            font-size: 16px; /* Ukuran font */
            color: #333; /* Warna teks */
            text-align: justify; /* Rata kanan-kiri */
        }

        /* Gaya untuk gambar */
        .item img {
            max-width: 100%; /* Membuat gambar responsif */
            height: auto; /* Menjaga rasio aspek gambar */
            border-radius: 5px; /* Sudut melengkung pada gambar */
            margin-bottom: 10px; /* Jarak antara gambar dan teks */
            width: 300px; /* Atur lebar gambar sesuai kebutuhan */
        }

        /* Gaya untuk gambar di header */
        header img {
            display: none; /* Menghilangkan gambar di header */
        }

        /* Gaya untuk teks Visi dan Misi */
        .vision-mission {
            text-align: justify; /* Rata kiri untuk Visi dan Misi */
        }
    </style>
</head>
<body>
    <header>
        <h1 class="gradient-text">Selamat Datang di CV. Mulia Globalindo Sejahtera</h1>
        <div class="divider"></div> <!-- Garis pembatas -->
    </header>
    
    <div class="container">
        <div class="item">
            <h2>Profil Perusahaan</h2>
            <img src="yyyyy.jpeg" alt="Image" height="42" width="42">
            <p class="text">CV. Globalindo Sejahtera adalah perusahaan yang bergerak sebagai distributor bahan bangunan di Malang. Perusahaan ini fokus pada penyediaan produk berkualitas tinggi dan layanan pelanggan yang responsif, serta berkomitmen untuk berkontribusi pada pembangunan infrastruktur yang berkelanjutan.</p>
            <p class="text">Berkembang sebagai bidang usaha distributor bahan bangunan</p>
            <strong class="vision-mission">VISI</strong>
            <p class="text vision-mission">untuk menjadi perusahaan distributor terbaik yang mengedepankan kualitas integritas dan profesionalisme</p>
            <strong class="vision-mission">MISI</strong>
            <p class="text vision-mission">Menjadi perusahaan yang paling unggul dalam setiap sektor (kualitas, distribusi dan inovasi)</p>
        </div>
        <div class="item">
            <h2>Produk</h2>
            <img src="https://th.bing.com/th/id/R.425cde2d61504e686db1c620d4db21de?rik=iX18rTDBXyyriw&riu=http%3a%2f%2fwww.rolledsteelsheet.com%2fphoto%2fps33678554-industrial_building_bright_surface_stainless_steel_u_channels_40x20x3mm.jpg&ehk=gtFGkbnfVPL8kp%2f8dhpeONEJJjDrhO%2bN1YG2xRWtf2Y%3d&risl=&pid=ImgRaw&r=0" alt="Deskripsi Item 2">
            <p class="text">Deskripsi singkat tentang item 2.</p>
        </div>
        <div class="item">
            <h2>Lokasi</h2>
            <img src="ttttt.png" alt="Lokasi">
            <p class="text">Alfamart, Jl. Raya Klampok RT4 RW 4 (timur, Klampok, Kec. Singosari, Kabupaten Malang, Jawa Timur 65153)</p>
        </div>
    </div>
</body>
</html>
