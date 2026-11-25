# Week 2 - SQL Cleaning

## Eesmärgid:
- Nädal 2 eesmärgiks oli tuvastada probleeme UrbanStyle andmetes/tabelites ning teostada nende korrastus ja puhastus
- Õppisime ja kasutasime käsklusi/funktsioone: GROUP BY, HAVING, ROW_NUMBER,IS NULL, COALESCE, NULLIF,CAST, TRIM, UPPER/LOWER

Rollid oli jaotatud vastavalt teamcharter.md välja toodud rotatsioonile.   

## Mida leidsime:  

**ROLL A - Müügiandmete Puhastamine:**
- 4013 korduvat arvet mis annavad kokku 5116 duplikaati.
- 1487 puuduvat kliendi ID / "külalisostud"
- 305 negatiivse summaga arvet
- 50 arvet müügikuupäevast väljas pool (2026-02-28)

**ROLL B - Kliendiandmete Puhastamine:**
  

**ROLL C - Tooteandmete Puhastamine:**
- 12 korduvat tootenime, kõiki kordub tabelis 2 korda
- 18 NULL väärtust eco sertifikaadi väljal
- 0 NULL väärtust ülejäänud väljadel
- 10 loogika viga, kus jaehind on väiksem ostuhind (ÄRIRISK!)
- 0 negatiivset või äärmusliku hinda
- 0 ebajärjekindlust muudes veergudes  

**ROLL D - Ristvalideerimine ja Kvaliteedikontroll:**


## Meeskonna töö esitluse
**Link originaaldokumendile:** [Google Presentation  - Grupp 1](https://docs.google.com/presentation/d/190yRPVJ6Jh4i0KXX1RLcWT7VAmWsToKU61McgcWNw40/edit?usp=sharing)  
**Koopia asukoht Githubi kaustas:** [week-2/week_2_esitlus.pdf]()

