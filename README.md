# Dziki Gon: Bitwa o Main

**Krótkie podsumowanie i zasady gry**

To gra szkoleniowa, w której 4 drużyny współpracują w jednym repozytorium, aby stworzyć działający raport. 

Waszym zadaniem jest przeprowadzanie waszych zmian z gałęzi osobistej np. dev1_XX aż do końca dev. 

Ale uwaga! Nie możecie sabotować innych, wasze gałęzie mogą generować konflikty i wy musicie zdecydować, co przepuścić, co odrzucić a co zaakeceptować podwójnie. 

Zadania są z natury proste, natomiast ich celem jest zapoznanie się dokładniej z edytorem konfliktów. 

## Szkoły (Drużyny)

Zostaniecie podzieleni na 4 szkoły:

- Zakon Miary (Grupa 1)
- Szkoła Kalendarza (Grupa 2)
- Cech Barwy (Grupa 3)
- Gildia Kanwy (Grupa 4)

## Jak gramy?

Wszystkie chwyty dozwolone - używanie AI, przeszukiwanie historii, checkout itp., tak jak w prawdziwej sytuacji. Możecie współpracować między drużynami, szczególnie jeśli chodzi o konflikty w Git. 

### Etap 1: Próba Traw (Praca u siebie)

- Zaczynacie od tego, że każda osoba pracuje na przypisanej sobie gałęzi osobistej (np. `dev1_DG`), odbitej od gałęzi Waszej szkoły (np. `dev1`).
    
- Pracujecie indywidualnie - Niech każdy wykona swoje zadanie edycja wpisu, rozwiązanie konfliktu 
    
- Kiedy skończycie, robicie merge swojej gałęzi osobistej z powrotem do gałęzi szkoły (`dev1`, `dev2` itd.).
    
- Uwaga: W plikach tekstowych na pewno wystąpią konflikty - Waszym zadaniem będzie poprawne rozwiązanie ich (np. poprzez zachowanie obu wpisów), aby nie skasować pracy innych.  Innym razem musicie odrzucić zmiany bo coś może być źle :)
    

### Etap 2: Zjazd Szkół 
- Zaczyna się, gdy wszyscy w drużynie skończą Etap 1. 
    
- Cała szkoła siada razem do jednego ekranu i wykonuje scalenie swojej gałęzi grupowej do wspólnego `dev`.
    
- Spotkacie się tutaj z kodem innych drużyn. Konieczne będzie wspólne rozstrzyganie konfliktów z uwzględnieniem logiki całego raportu.
    
### Etap 3: Zjazd Szkół 
- Gdy wszystkie drużyny zmergują gałęzie do DEV, wówczas przeniesiemy zmiany do main. I to będzie rozstrzygnięcie, ponieważ porównamy wynik końcowy z oczekiwanym.
- Będzie tam czekało hasło szkoły, hasło całej gry oraz komentarze graczy.

Jeśli wszystko się uda - Żaden komentarz nie zginie, w przeciwnym wypadku zobaczymy, czy ktoś poległ na polu walki :)
## Dokumentacja

Szczegółowe instrukcje radzenia sobie z konfliktami, anatomia błędów (np. pułapka przecinka) oraz lista komend ratunkowych znajdują się w udostępnionym pliku PDF:

- **Git-Bitwa-O-Main-cheat-sheet.pdf** - to Wasza główna ściąga i przewodnik po rozwiązywaniu problemów z gitem. Zawsze zaglądajcie tam, zanim podejmiecie decyzję w edytorze scalania.
- **Git-challenge-bitwa-o-main** - Dokładna instrukcja gry
