Домашно: Биене на дузпи
===

- Създайте клас `FootballPlayer`, който като минимум има оценка за стрелба/изпълнение на дузпи и пазене
- Създайде клас `Team`. Отборът трябва да знае кой ще пази дузпите и кои са изпълнителите
- Създайте клас `PenaltyShootout`, който получава двата отбора и има метод, управляващ биенето на дузпите
- Измислете метод за определяне на успех при биенето на дузпите
- Създайте два отбора. Не е нужно да са от по 11, достатъчно е да са поне 5. 
- Задължително е двата отбора да бъдат с еднакъв брой състезатели
- Бийте дузпите като играчи от двата отбора се редуват. Бият се по 5 дузпи, освен ако един от двата отбора загуби шанс за поне равенство при 5 изпълнения. При равенство след 5 дузпи - продължава изпълнение 1 по 1 докато се наруши равенството след еднакъв брой изпълнени дузпи.  
- Изведете резултата. 

Пример за генериране на случайни числа
===

```
#include <iostream>
#include <chrono>

using namespace std;

int main() {
    // this needs to be done once, do it in main
    srand(time(NULL));

    cout << "This is a random value in the range [0, 1]: " << (double) rand() / RAND_MAX << endl;
    cout << "This is a random value in the range [0, 1]: " << (double) rand() / RAND_MAX << endl;
    cout << "This is a random value in the range [0, 1]: " << (double) rand() / RAND_MAX << endl;

    return 0;
}
```