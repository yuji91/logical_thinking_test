Q1. 「RUNTEQはプログラミングスクールである」の命題が真であるとする。

以下の命題で真となるものはどれか。
1. 「プログラミングスクールはRUNTEQである」
2. 「RUNTEQでないならプログラミングスクールではない」
3. 「プログラミングスクールでないならRUNTEQではない」

A1.【解答：3】  
【解説】
1については、プログラミングスクールであるからといって、RUNTEQであるとは限りません。また真の命題に対する逆なので、常に正しいとは限らないので偽となります。  
2については、RUNTEQでないことで、プログラミングスクールでないとは限りません。また真の命題に対する裏なので、常に正しいとは限らないので偽となります。  
3については、RUNTEQはプログラミングスクールであることを前提としているので、プログラミングスクールでないものはRUNTEQでないことは成り立ちます。  
また真の命題に対する対偶なので、常に正しいため真となります。  

【余談】  
この問題が最も簡単で、命題に対する逆、裏が真とならないことを知ってもらう意図があります。  

※ 元は「雪は白い」が命題で
1. 「白いものは雪である」逆 --> 偽
2. 「雪でないなら白くない」裏 --> 偽
3. 「白くないものは雪ではない」対偶 --> 真
上記が正しいのですが、現実では黒く濁った雪などもあり得るので対偶が真だと選びづらいと感じたため、プログラミングスクール関連の問題にしてみました。


---

Q2. 国語と数学のテストを70名に行ったところ、以下の結果となった。  
1. 国語の合格点を取った人が30名  
2. 数学の合格点を取った人が20名  
3. 国語、数学どちらも不合格だった人が25名  

テストを受けた人のうち、国語と数学どちらも合格点を取った人は何名か

A2.【解答：5名】  
【解説】
分かりづらい場合は、ベン図などを紙に書いてみると考えやすいと思います。
まず【全体：70名】から【どちらも不合格：25名】を引いて【少なくともどちらかは合格：45名】を算出します。  
これによって【国語の合格点を取った人：30名】を引くと【数学のみ合格点を取った人：15名】が算出できます。  
ここで【国語の合格点を取った人：30名】は【国語のみ合格点を取った人】と【国語と数学とちらも合格点を取った人】の人数の合計であることに注意してください。  

同様に【少なくともどちらかは合格：45名】から【数学の合格点を取った人：20名】（数学のみ + 数学と国語で合格）を引くと【国語のみ合格点を取った人：25名】が算出できます。  

【国語の合格点を取った人：30名】（国語のみ + 国語と数学両方）から【国語のみ合格点を取った人：25名】を引くと【国語と数学とちらも合格点を取った人：5名】が算出できます。  
【数学の合格点を取った人：20名】（数学のみ + 国語と数学両方）から【数学のみ合格点を取った人：15名】を引くと【国語と数学とちらも合格点を取った人：5名】が算出できるので、整合性が取れています。  

【余談】  
この問題は最後の問題を除いて2番目に難しいと思います。  
【国語の合格点を取った人】＝（国語のみ + 国語と数学両方）であることを変換してどんな値を算出すれば良いかをイメージする必要があります。  

---

Q3. 目の前に天国への分かれ道があった。

以下の内容が正しい場合、どちらの道に行けば確実に天国に行けるか。
- 左と右のうち、少なくとも片方は天国である
- 左の道が天国だった場合、右の道も天国である

A3.【解答：右】  
【解説】
どちらか片方は天国なので、どちらのケースも場合分けして考えると良いです。  
左の道が天国だった場合、右の道も天国になります。【1. 左：天国, 右：天国】  
右の道が天国だった場合は、左の道が天国であるかどうかは分かりませんが、右の道は天国に行けます。  
そのため、右の道が必ず天国に行けると言えます。  

ちなみに全てのケースを整理すると、以下のようになります。  
【1. 左：天国, 右：天国】   
【2. 右：天国, 左：天国】   
【3. 右：天国, 左：?】   
右の道だけが、天国であることが分かります。  

【余談】  
「右の道が天国だった場合では、左の道が天国であるかどうかは分からない。」ということを前提に考える必要があります。  

---

Q4. 県で盗難事件が発生し、次の情報が警察に寄せられた。  
- 「A，B，Cの誰かが犯人です。」
- 「Aが犯人なら，Bも犯人です。」
- 「Bが犯人なら，Cも犯人です。」
これらの情報がすべて正しい場合、確実に犯人だと言える1名は誰か  

A4.【解答：C】  
【解説】 
このケースも場合分けを行います。
【Aが犯人だった場合：A：犯人, B：犯人, C：犯人】  
【Bが犯人だった場合：A：?, B：犯人, C：犯人】  
【Cが犯人だった場合：A：?, B：?, C：犯人】  
どのケースでもCは確実に犯人だと言えます。  

【余談】 
考えられるすべてのパターンを場合分けして考える必要があります。  

---

Q5. A，B，C，D，Eの5人が，誰が宝くじを当てたかについて話し合いをしている。  
本当のことを言っているのは2人で，残りの3人はウソをついている。  
- A「Bが宝くじを当てた。」
- B「僕は当てていない。」
- C「Eが宝くじを当てた。」
- D「Aはウソをついている。」
- E「Cはウソをついている。」

宝くじを当てたのは誰か。  

A5.【解答：B】  
【解説】 
以下の宝くじが当たった発言に対して、【両方の発言が本当の場合】と【片方の発言のみ本当の場合】のそれぞれが成立するかどうかを場合分けして考えます。  
- A「Bが宝くじを当てた。」
- C「Eが宝くじを当てた。」

【両方本当だった場合：本当の発言は2人という条件があるので、以下のように他3人がウソとなります。】
- A「Bが宝くじを当てた。（本当）」（本当であると仮定）
- B「僕は当てていない。（ウソ）」--> 「Bが宝くじを当てた」となるので、Aと成り立つ
- C「Eが宝くじを当てた。（本当）」（本当であると仮定）
- D「Aはウソをついている。（ウソ）」--> Aは本当「Bが宝くじを当てた」となるので、成り立つ
- E「Cはウソをついている。（ウソ）」--> Cは本当「Eが宝くじを当てた」となるので、成り立つ

【両方の発言が本当の場合】は【BとEが宝くじを当てた】ことが成立します。  

【Aの発言が本当で、Cの発言がウソだった場合】
- A「Bが宝くじを当てた。（本当）」（本当であると仮定）
- B「僕は当てていない。（ウソ）」--> Aを成り立たせるために、Bはウソである必要がある
- C「Eが宝くじを当てた。（ウソ）」（ウソであると仮定）--> Eは宝くじを当てていない
- D「Aはウソをついている。（ウソ）」--> Aを成り立たせるために、Dはウソである必要がある
- E「Cはウソをついている。（本当）」--> Cがウソである場合、Eは宝くじを当てていないことになります

Cがウソである仮定を成り立たせるためには、A以外にもEが本当のことを言っていると仮定する必要があります。    
この仮定は成り立つので、【Aの発言が本当で、Cの発言がウソだった場合】は【Bが宝くじを当ててEが当てていない】ケースが成立します。  

【Aの発言がウソで、Cの発言が本当だった場合】
- A「Bが宝くじを当てた。（ウソ）」（ウソであると仮定）
- B「僕は当てていない。（本当）」--> Aを成り立たせるために、本当である必要がある
- C「Eが宝くじを当てた。（本当）」（本当であると仮定）
- D「Aはウソをついている。（本当）」--> Aを成り立たせるために、本当である必要がある
- E「Cはウソをついている。（ウソ）」--> Cを成り立たせるために、ウソである必要がある
Cが本当でAはウソあると仮定した場合、BもDの発言も本当である必要があるので、【本当の発言は2人】という問題の条件を満たせないので成立しません。  

これらの場合分けを考えると【BとEが宝くじを当てた場合】と【Bのみが宝くじを当てた場合】が考えられます。  
どちらの場合も宝くじを当てているのはBなので、Bが正解と言えます。  

【余談】 
曖昧な状況から、どのように場合分けしていけば良いかを考えて、成立しうるケースから確実に宝くじを当てた人を導き出す必要があります。  
また【BとEが宝くじを当てた場合】だけでなく【Bのみが宝くじを当てた場合】が成立することも検討して【Eが宝くじを必ず当てるとは言えない】ことも把握しなければいけません。  
