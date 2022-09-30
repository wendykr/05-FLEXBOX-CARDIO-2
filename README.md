# Ahoj Karkulko.

Zlý vlk ti snědl babičku. Záchránit ji můžeš jedině tak, že nakóduješ spoustu layoutů pomocí flexboxu!

V každé složce máš zadání úkolu ve formě obrázku a připravený "prázdný" HTML a CSS soubor. Musíš si sama napsat HTML tak, abys ho pak uměla nastylovat v CSS přesně podle obrázku. Samozřejmě pomocí flexboxu.

Na velikostech sloupců nijak zvlášť nezáleží, ale ber to tak, že ty "úzké" sloupce na obrázcích zabírají vždy `20%` šířky obrazovky (nebo `20vw`). Jsou-li vodorovně (hlavička, patička), mají výšku `20%` okna prohlížeče (neboli `20vh`).

## Jednotky

Jak už předchozí odstavec naznačuje, pro šířku jednotlivých prvků můžeš použít procenta. Ta mohou být někdy obtížná na použití, protože se vždy vztahují k šířce/výšce rodičovského prvku. Pokud tedy něčemu nastavíš šířku `20%`, znamená to 20% z rodiče tohoto prvku. Je-li sám rodič široký třeba 50% stránky, bude tvůj prvek široký 10% stránky (20% z 50%). Procenta jsou extrémně užitečná jednotka, ale v některých případech se hodí jednotky jiné.

Jednotky **vw** a **vh** jsou zkratky pro *viewport width* a *viewport height*. `100vw` představuje šířku okna prohlížeče, `100vh` představuje výšku okna prohlížeče. Když mluvíme o okně prohlížeče, nemyslíme v tomto případě celé okno s adresním řádkem a dalšími lištami a tlačítky, ale pouze výřez okna, který má pro k dispozici stránka - tzv. **viewport**.

Protože `100vw` představuje šířku okna/stránky, když něčemu nastavíme šířku `20vw`, bude prve zabírat vždy pětinu šířky okna, nezávisle na tom, jakou šířku má nastavenou rodič prvku. To stejné platí pro výšku. Když něčemu nastavíme výšku `100vh`, bude to vysoké přesně jako celý viewport.

## Sémantické značky

Pro hlavní bloky celé stránky použij sémantické značky `<header>`, `<footer>`, `<article>`, `<nav>`, `<aside>`. Občas je budeš muset zabalit do dalšího `<div>`u, protože některé layouty používají do sebe vnořené flexboxy.

V prvním příkladu máš HTML připravené, abys měla představu, co po tobě chci. CSS už ale vymysli sama. Samotný CSS kód je většinou velmi krátký.

Nepouštěj se do kódování bezhlavě. Tvým úkolem je hlavně **myslet**! Příklady nejsou extra složité, jen musíš vymyslet, jak prvky poskládat, jak je potřebuješ vnořit do jiných prvků (pokud vůbec), případně kdy ve flexboxu nastavit `flex-wrap` a další vlastnosti.

Hodně štěstí,
*Tvůj zlý Vlk!*