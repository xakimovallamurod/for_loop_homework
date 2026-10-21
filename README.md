# for sikli

## For01

n soni berilgan. 0 dan n gacha (n ham kiradi) bo'lgan sonlarni ro'yxat ko'rinishida qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: n=5
Chiqarish: [0, 1, 2, 3, 4, 5]
```

**Misol 2:**

```Python
Kirish: n=0
Chiqarish: [0]
```

---

## For02

n soni berilgan. 0 dan n gacha (n ham kiradi) bo'lgan sonlarni bo'sh joy bilan ajratilgan satr ko'rinishida qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: n=3
Chiqarish: "0 1 2 3"
```

**Misol 2:**

```Python
Kirish: n=0
Chiqarish: "0"
```

---

## For03

k va n sonlari berilgan. k sonini n marta takrorlab, ro'yxat ko'rinishida qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: k=26, n=3
Chiqarish: [26, 26, 26]
```

---

## For04

a va b sonlari berilgan (a < b). a dan b gacha (ikkalasi ham kiradi) bo'lgan sonlarni ro'yxat ko'rinishida qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: a=2020, b=2026
Chiqarish: [2020, 2021, 2022, 2023, 2024, 2025, 2026]
```

---

## For05

a va b sonlari berilgan (a < b). b dan a gacha (ikkalasi ham kiradi) kamayish tartibida sonlarni ro'yxat ko'rinishida qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: a=1, b=5
Chiqarish: [5, 4, 3, 2, 1]
```

---

## For06

a va b sonlari berilgan (a < b). a dan b gacha (ikkalasi ham kiradi) bo'lgan barcha sonlar yig'indisini qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: a=1, b=100
Chiqarish: 5050
```

**Misol 2:**

```Python
Kirish: a=20, b=26
Chiqarish: 161
```

---

## For07

n soni berilgan. 1 dan n gacha (n ham kiradi) bo'lgan toq sonlar yig'indisini qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: n=10
Chiqarish: 25
```

**Misol 2:**

```Python
Kirish: n=7
Chiqarish: 16
```

---

## For08

n soni berilgan. 1 + 1/2 + 1/3 + … + 1/n yig'indisini hisoblang va 2 xona aniqlikda yaxlitlab qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: n=4
Chiqarish: 2.08
```

**Misol 2:**

```Python
Kirish: n=1
Chiqarish: 1.0
```

---

## For09

Allamurod bozordan olma olmoqchi. 1 kg olma narxi berilgan. 1 dan 10 kg gacha olmaning narxlarini ro'yxat ko'rinishida qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: narx=12000
Chiqarish: [12000, 24000, 36000, 48000, 60000, 72000, 84000, 96000, 108000, 120000]
```

---

## For10

Kichik harflar bilan yozilgan ismlar ro'yxati berilgan. Har bir ismni bosh harf bilan boshlab, yangi ro'yxat qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: ismlar=["allamurod", "akmal", "dilshod"]
Chiqarish: ["Allamurod", "Akmal", "Dilshod"]
```

---

## For11

Allamurodda n ta har xil kitob bor. Ularni javonga necha xil tartibda terish mumkinligini (n!) hisoblab qaytaring. `math` modulidan foydalanmang. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: n=5
Chiqarish: 120
```

**Misol 2:**

```Python
Kirish: n=1
Chiqarish: 1
```

---

## For12

Ismlar ro'yxati berilgan. "A" harfi bilan boshlanadigan ismlarni yangi ro'yxatga yig'ib qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: ismlar=["Allamurod", "Dilshod", "Akmal", "Sardor"]
Chiqarish: ["Allamurod", "Akmal"]
```

---

## For13

n soni berilgan. 1 dan n gacha (n ham kiradi) bo'lgan, 3 ga yoki 5 ga bo'linadigan sonlar yig'indisini qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: n=10
Chiqarish: 33
```

**Misol 2:**

```Python
Kirish: n=15
Chiqarish: 60
```

---

## For14

n soni berilgan. Uning 1 dan 10 gacha ko'paytirish jadvalini "n x i = natija" ko'rinishidagi satrlar ro'yxati sifatida qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: n=7
Chiqarish: ["7 x 1 = 7", "7 x 2 = 14", "7 x 3 = 21", "7 x 4 = 28", "7 x 5 = 35", "7 x 6 = 42", "7 x 7 = 49", "7 x 8 = 56", "7 x 9 = 63", "7 x 10 = 70"]
```

---

## For15

Allamurod har oy oxirida jamg'armaga bir xil summa qo'yadi, jamg'armaga esa har oy foiz qo'shiladi. Oylik qo'yilma, oylar soni va oylik foiz berilgan. Har oy: summa = summa · (100 + foiz) / 100 + oylik. Yakuniy summani 2 xona aniqlikda yaxlitlab qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: oylik=1000000, oylar=3, foiz=2
Chiqarish: 3060400.0
```

**Misol 2:**

```Python
Kirish: oylik=500000, oylar=1, foiz=5
Chiqarish: 500000.0
```

---

## For16

So'zlar ro'yxati berilgan. Har bir so'zning uzunligidan iborat yangi ro'yxat qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: sozlar=["Allamurod", "Xakimov", "Toshkent"]
Chiqarish: [9, 7, 8]
```

---

## For17

n soni berilgan. 2 dan n gacha (n ham kiradi) bo'lgan tub sonlarni ro'yxat ko'rinishida qaytaring. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: n=20
Chiqarish: [2, 3, 5, 7, 11, 13, 17, 19]
```

**Misol 2:**

```Python
Kirish: n=2
Chiqarish: [2]
```

---

## For18

n soni berilgan (n ≥ 2). Fibonachchi ketma-ketligining dastlabki n ta hadini ro'yxat ko'rinishida qaytaring (0, 1, 1, 2, 3, ...). `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: n=8
Chiqarish: [0, 1, 1, 2, 3, 5, 8, 13]
```

**Misol 2:**

```Python
Kirish: n=2
Chiqarish: [0, 1]
```

---

## For19

Allamurodning test ballari ro'yxati berilgan. Har bir ballni bahoga aylantirib, baholar ro'yxatini qaytaring: 86–100 → 5, 71–85 → 4, 56–70 → 3, qolganlari → 2. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: ballar=[87, 92, 78, 60, 40]
Chiqarish: [5, 5, 4, 3, 2]
```

---

## For20

n soni berilgan. n qatorli yulduzchali piramidani satrlar ro'yxati ko'rinishida qaytaring: i-qatorda (1 dan boshlab) n − i ta bo'sh joy va 2·i − 1 ta `*` bo'lsin. `for` siklidan foydalaning.

**Misol 1:**

```Python
Kirish: n=3
Chiqarish: ["  *", " ***", "*****"]
```

**Misol 2:**

```Python
Kirish: n=1
Chiqarish: ["*"]
```

