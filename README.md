# Yazı Atölyesi — Statik Website

4 haftalık çevrimiçi yaratıcı yazarlık atölyesi için tanıtım sitesi. Saf HTML/CSS/JS — derleme adımı yok.

## Nasıl açılır?
`index.html` dosyasına çift tıklayın veya terminalde:

```bash
open index.html
```

Küçük bir yerel sunucu isterseniz:

```bash
python3 -m http.server 8000
# sonra tarayıcıda: http://localhost:8000
```

## Dosya yapısı
```
Websitem/
├── index.html      # Tek sayfa, tüm bölümler
├── css/styles.css  # Stiller (renkler en üstteki :root değişkenlerinde)
├── js/main.js      # Mobil menü + scroll animasyonları
└── README.md
```

## İçeriği düzenleme
Tüm metinler `index.html` içinde, bölümler yorum satırlarıyla (`<!-- Hafta 1 -->`) işaretli.
Aşağıdaki yer tutucuları kendi bilgilerinizle değiştirin:

- `[Eğitmen Adı]` ve eğitmen biyografisi (Eğitmen bölümü)
- `[adiniz@eposta.com]` — kayıt e-postası (Kayıt bölümü, 2 yerde)
- `[tarih]`, `[ücret bilgisi]` (Kayıt bölümü)
- Katılımcı yorumları (taslaktır, gerçek yorumlarla değiştirilebilir)

## Renkleri değiştirme
`css/styles.css` dosyasının en üstündeki `:root` bloğundan tek noktadan değiştirebilirsiniz
(`--accent`, `--bg`, `--ink` vb.).
