# GearX — savāc zobratus

Spēles mērķis: palīdzēt robotam savākt zobratus, lai tā mehānisms atkal grieztos.

## Mapju struktūra un atvēršana
- `index.html` — galvenā spēles sākumlapa
- `atteli/` — paša zīmēts PNG varonis
- `skanas/` — spēles skaņas efekts

Atvēršana: atver `index.html` interneta pārlūkā no projekta mapes.

## Dizaina izvēles un pārbaude
- Tumši zils fons ar gaišu tekstu rada kosmosa noskaņu un skaidru kontrastu visās četrās zonās.
- Spēles laukums ir centrēts ar `margin: 20px auto`, tam ir 20px iekšējā atstarpe un raupjš raustīts rāmis, kas vizuāli atdala spēles zonu no pārējās lapas.
- Poga ir gaiši zila akcents ar baltu, treknraksta tekstu — tā ir pamanāma uz tumšā fona.
- Pārbaudīts: attēls, skaņa un punktu skaitītājs (3 klikšķi = 3 punkti) darbojas, arī sašaurinātā logā bez horizontālās ritjoslas.
- Klasesbiedra atsauksme un uzlabojums: sākumā pogas teksts bija grūti pamanāms, tāpēc palielināju pogas fonta izmēru un pievienoju treknrakstu.