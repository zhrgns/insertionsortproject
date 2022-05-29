# INSERTION SORT PROJESI  for PATIKA.DEV
---
## Verilen dizinin Insertion Sort dizilimi

1. Unsorted Order

```
[22,27,16,2,18,6]
```

2. Insertion Sort ilk iki elementi karşılaştırır. 22 ve 27 dizilimi doğru olduğu için ilk adım değişiklik yapılmadan 22 sayısı için tamamlandı.

```
[22,27,16,2,18,6]
[22,27,16,2,18,6]
```

3. 27 ve 16 sayıları dizilimi karşılaştırılır. 16<27 olduğundan swaplanır.

```
[22,27,16,2,18,6]
[22,16,27,2,18,6]
```

4. Düzenlenmiş sub-list kendi içinde tekrar karşılaştırılır. 16<22 olduğundan swaplanır.

```
[22,16,27,2,18,6] 
[16,22,27,2,18,6]
```

5. Sub-list düzenlendi. İşlem kaldığı yerden devam eder. 2<27 olduğundan swaplanır.

```
[16,22,27,2,18,6]
[16,22,2,27,18,6]
```

6. Düzenlenmiş sub-list kendi içinde tekrar karşılaştırılır. 2<22 olduğundan swaplanır. 2<16 olduğundan tekrar swaplanır. 

```
[16,22,2,27,18,6]
[16,2,22,27,18,6]
[2,16,22,27,18,6]
```

7. Sub-list düzenlendi. İşlem kaldığı yerden devam eder. 18<27 olduğundan swaplanır. Düzenlenmiş sub-list kendi içinde tekrar karşılaştırılır. 18<22 olduğundan swaplanır. 2<16 olduğundan tekrar swaplanır. 
(Sub-list orderlanana kadar bu işlemler devam eder.)

```
[2,16,22,27,18,6]
[2,16,22,18,27,6]
[2,16,18,22,27,6]
```

8. Sub-list düzenlendi. İşlem kaldığı yerden devam eder. 6<27 olduğundan swaplanır. Düzenlenmiş sub-list kendi içinde tekrar karşılaştırılır. 6<22 olduğundan swaplanır. 6<18 olduğundan tekrar swaplanır. 

```
[2,16,18,22,27,6]
[2,16,18,22,6,27]
[2,16,18,6,22,27]
[2,16,6,18,22,27]
[2,6,16,18,22,27]
```

9. Sub-list düzenlendi. 27'nin sağında karşılaştıracak elemen kalmadığı için işlem tamamlandı.

```
Sorted Order: [2,6,16,18,22,27]
```


## Big O'Notation

    O(N^2)

## Time Complexity


    18 sayısı dizinin ortalarına gelecektir. Bu sebeple bu dizide time complexity **Average Case** dir.

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı
```
[7,3,5,8,2,9,4,15,6]
[3,7,5,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
[3,5,7,2,8,9,4,15,6]
```

---
### License
[MIT](https://choosealicense.com/licenses/mit/)
