### 🟩 Task01

**Foydalanuvchi ismi va yoshi asosida xabar chiqarish**
`format()` methodidan foydalanib, matnga foydalanuvchi ma’lumotlarini joylashtiring.

| Input                                                           | Output                                       |
| --------------------------------------------------------------- | -------------------------------------------- |
| `"Salom, mening ismim {} va yoshim {}.".format("Diyorbek", 23)` | `Salom, mening ismim Diyorbek va yoshim 23.` |

---

### 🟩 Task02

**Narxlar ro‘yxatini matnda ko‘rsatish**
Mahsulot nomi va narxini matnga joylashtiring.

| Input                                          | Output                      |
| ---------------------------------------------- | --------------------------- |
| `"{} mahsuloti narxi ${}".format("Olma", 1.5)` | `Olma mahsuloti narxi $1.5` |

---

### 🟩 Task03

**Fayl nomi va kengaytmasini chiqarish**
Fayl nomi va uning turini `format()` yordamida ko‘rsating.

| Input                                   | Output             |
| --------------------------------------- | ------------------ |
| `"Fayl: {}.{}".format("report", "pdf")` | `Fayl: report.pdf` |

---

### 🟩 Task04

**Hafta kuni va dars soatini yozish**
Kun va soatni formatda chiqarish.

| Input                                                      | Output                                  |
| ---------------------------------------------------------- | --------------------------------------- |
| `"Bugun {} kuni, dars soat {} da.".format("Dushanba", 14)` | `Bugun Dushanba kuni, dars soat 14 da.` |

---

### 🟩 Task05

**Ikki raqamdan iborat amaliy natijani formatlash**
Matematik amalni ifodalashda formatdan foydalaning.

| Input                             | Output       |
| --------------------------------- | ------------ |
| `"{} + {} = {}".format(5, 7, 12)` | `5 + 7 = 12` |

---

### 🟨 Task06

**Emaildagi `@` belgisining indeksini toping**
Email adresidagi `@` belgisi nechinchi pozitsiyada turganini aniqlang.

| Input                       | Output |
| --------------------------- | ------ |
| `"ali@gmail.com".find("@")` | `3`    |

---

### 🟨 Task07

**Matnda ma’lum bir so‘zning boshlanish pozitsiyasini topish**
`index()` orqali `Python` so‘zi qayerdan boshlanganini toping.

| Input                                                       | Output |
| ----------------------------------------------------------- | ------ |
| `"Men Python dasturlash tilini o‘rganaman".index("Python")` | `4`    |

---

### 🟨 Task08

**Bir so‘z bir necha marta qatnashgan bo‘lsa, birinchi indeksni toping**
Faqat birinchi topilgan joyni chiqaring.

| Input                                               | Output |
| --------------------------------------------------- | ------ |
| `"kitoblar kitob do‘konida sotiladi".find("kitob")` | `0`    |

---

### 🟨 Task09

**Belgilarni qayerdan boshlab qidirishni aniqlang**
`find()` metodiga start pozitsiyasi bilan ishlang.

| Input                            | Output |
| -------------------------------- | ------ |
| `"salom salom".find("salom", 2)` | `6`    |

---

### 🟨 Task10

**Topilmagan so‘zlar uchun -1 natija berilishini tushuning**
`find()` orqali mavjud bo‘lmagan so‘zni qidiring.

| Input                       | Output |
| --------------------------- | ------ |
| `"Hello world".find("bye")` | `-1`   |

---

## 🔢 **11–15: String Counting (`count()` method)**

---

### 🟧 Task11

**Matnda `a` harfi nechta ekanligini sanang**

| Input                                | Output |
| ------------------------------------ | ------ |
| `"salom, qanday ishsiz?".count("a")` | `3`    |

---

### 🟧 Task12

**So‘zda bo‘sh joylar sonini toping**

| Input                                         | Output |
| --------------------------------------------- | ------ |
| `"Bu Python darsi juda qiziqarli".count(" ")` | `4`    |

---

### 🟧 Task13

**Matnda `@` belgisi necha marta qatnashganini toping**

| Input                                         | Output |
| --------------------------------------------- | ------ |
| `"user1@mail.com, user2@mail.com".count("@")` | `2`    |

---

### 🟧 Task14

**Berilgan substring (`py`) necha marta qatnashganini toping**

| Input                        | Output |
| ---------------------------- | ------ |
| `"pythonpyPYpy".count("py")` | `2`    |

---

### 🟧 Task15

**Gapda nuqta (`.`) necha marta qatnashganini sanang**

| Input                                   | Output |
| --------------------------------------- | ------ |
| `"file.txt.2025.report.doc".count(".")` | `3`    |

---

### 🟦 Task16

**Foydalanuvchining ismi faqat harflardan iboratligini tekshiring**
Saytdagi ro‘yxatdan o‘tishda ismlar `isalpha()` bilan tekshiriladi.

| Input                  | Output |
| ---------------------- | ------ |
| `"Diyorbek".isalpha()` | `True` |

---

### 🟦 Task17

**Parol kamida 1 ta raqamdan iboratmi?**
Ro‘yxatdan o‘tishda `isdigit()` orqali raqam mavjudligi tekshiriladi.

| Input                 | Output  |
| --------------------- | ------- |
| `"pass123".isdigit()` | `False` |

---

### 🟦 Task18

**Foydalanuvchi kiritgan kod faqat raqamlardan iboratligini tekshirish**

| Input              | Output |
| ------------------ | ------ |
| `"2025".isdigit()` | `True` |

---

### 🟦 Task19

**Mahsulot nomlarini kichik harfga o‘tkazish (`lower()`)**
Katta harf/kichik harf farqini yo‘qotish uchun foydali.

| Input               | Output    |
| ------------------- | --------- |
| `"Telefon".lower()` | `telefon` |

---

### 🟦 Task20

**Sarlavhani `title()` yordamida formatlash**
Blog sarlavhalarini silliqlash uchun ishlatiladi.

| Input                               | Output                    |
| ----------------------------------- | ------------------------- |
| `"python dasturlash kursi".title()` | `Python Dasturlash Kursi` |

---
