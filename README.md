# Z-Code Helper
Ini adalah fungsi-fungsi yang sering kami gunakan dalam pengembangan perangkat lunak.

# Daftar Isi

- [Install](#install)
- [Penggunaan](#penggunaan)
- [Padding](#padding)
- [Format Number](#format-number)
- [Running Date](#running-date)

# Install

```
npm install zcode-helper --save
```

# Penggunaan

```javascript
const { pad } = require("zcode-helper");
const zeropad = pad (12, 4);
console.log(zeropad);
```

### Output
```
0012
```

# Padding
Digunakan untuk menambahkan karakter khusus (biasanya nol) di depan bilangan sehingga menjadi panjang karakter tertentu.
Contoh padding 4 karakter menggunakan karakter nol:
| Input | Output |
| ----- | ----- |
| 1 | 0001 |
| 12 | 0012 |
| 123 | 0123 |
| 1234 | 1234 |


# Format Number

# Running Date
