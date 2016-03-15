Commands:
=========

X specifies a number  
Arguments between ( ) are optional


Manager
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!afklimit | X |  ustawia maksymalny czas AFK |
|!botname | (botname) | zmienia domyślną nazwę bota |
|!bouncer+ | | przełącza bouncer+ |
|!skippos | X | ustawia pozycję do której skip i lockskip przenosi dj |
|!clearchat | |wyczyszcza chat |
|!cykl | | przełącza cykl DJ |
|!cycletimer | X | ustawia maksymalny czas cyklu DJ podczas włączonego cycleguard'a |
|!language | (language) | ustawia język jakim ma się posługiwać bot |
|!locktimer | X | ustawia maksymalny czas zablokowania waitlisty, jeśli lockguard jest włączony |
|~~!maxlength~~ | ~~X~~ | ~~ustawia maksymalną długość odtwarzania muzyki kiedy timeguard jest włączony~~ |
|!logout | | wylogowuje bota |
|!refresh | | odświeża przeglądarke na której działa bot |
|!usercmdcd | X | ustawia cooldown dla komend zwykłych użytkowników |
|!usercommands | | włącza/wyłącza komendy dla użytkowników |
|!voteskip | (X) | ustawia liczbę głosów aby pominąć nutę|

Bouncer+
--------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!add | @user | dodaje osobę do waitlist |
|!afkremoval | | włącza/wyłącza sprawdzanie afk |
|!autoskip | | skipuje piosenki automatycznie jak się skończą (używaj kiedy cykl się buguje) |
|!deletechat | @user | usuwa wszystkie wiadomości danej osoby |
|!lock | | zablokuj waitlist |
|!lockdown | | zablokowuje pokój: tylko dla moderacji chatu |
|!move | @user (X) | przenosi osobę na pozycję X w waitlist, domyślna to 1 |
|!remove | @user | usuwa użytkownika z listy czekania waitlist |
|!roulette | | zaczyna roulette |
|!songstats | | włącza/wyłącza statystyki muzyk |
|!unlock | | odblokowuje waitlist |
|!welcome | | włącza/wyłącza wiadomość powitalną dla dołączających użytkowników |

Bouncer
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!active | (X) | pokazuje ile użytkowników chatowało w czasie X ostatnich minut. Jeżeli X nie jest określony, 60 jest ustawione domyślnie |
|!afkreset | @user | resetuje czas AFK dla użytkownika |
|!afktime | @user | pokazuje jak długo użytkownik jest AFK |
|!autodisable | | włącza/wyłącza autodisable |
|!ban | @user | banuje użytkownika na 1 dzień |
|!blacklist / !bl | blacklistname | dodaje muzykę do blacklisty |
|!commanddeletion | | włącza/wyłącza jeżeli komendy bota zostają usuwane |
|!blinfo | | daje informację, czy dana piosenka należy do blacklisty  |
|!cycleguard | | włącza/wyłącza cycleguard |
|!dclookup / !dc | (@user) | robi dclookup dla użytkowników |
|!english | @user | prosi użytkownika o porozumiewanie się w języku angielskim |
|!eta | (@user) | pokazuje kiedy użytkownik będzie przy stoisku DJ |
|!filter | | włącza/wyłącza filtr chatu |
|!forceskip | | forceskips aktualną muzykę |
|!historyskip | | włącza/wyłącza history skip |
|!jointime | @user | pokazuje jak długo użytkownik jest w tym pokoju |
|!kick | (X) | kickuje użytkownika  na X minut, domyślnie-0.25 minuty (15 sekund) |
|!kill | | wyłącza bota |
|!lockguard | | włącza/wyłącza lockguard |
|!lockskip | (reason) | skipuje, lockuje i przenosi  dj (pozycję można ustawić za pomocą !skippos) |
|!motd | (X)/(message) | wiadomość dnia co X piosenek |
|!mute | @user (X) | mute użytkownika na X minut, jeśli X nie zostanie określony, to zostanie zmutowany na zawsze |
|!restricteta | | włącza/wyłącza ograniczenie eta: zwykli użytkownicy mogą użyć tylko raz na godzinę |
|!sessionstats | | pokazuje statystyki dla aktualnej sesji |
|!skip | (reason) | skipuje dj'a używając smartskip'a, działa jak lock i move użytkownika zależnie od różnych czynników (pozycja na którą dj jest przeniesiony można ustawić za pomocą !skippos)|
|!status | | pokazuje status bota i parę jego ustawień |
|!timeguard | | włącza/wyłącza timeguard |
|!togglebl | | włącza/wyłącza blacklist |
|!togglemotd | | włącza/wyłącza motd |
|!togglevoteskip | | włącza/wyłącza voteskip |
|!unban | @user | unban użytkownika |
|!unmute | | unmute użytkownika |
|!voteratio | @user | pokazuje statystyki głosowania przez użytkownika |
|!whois | @user | pokazuje informacje na temat użytkownika |

Resident DJ
-----------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!link | | daje link do aktualnej muzyki



User
----

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!8ball | (message) | zadaj botowi pytanie, bot może odpowiedzieć tak albo nie w zależności od pytania |
|!autowoot | | autowootuje muzyki |
|!ba | | informacje na temat Brand Ambassador rank |
|!slots | | zagraj w slots |
|!commands | | daje link do komend |
|!cookie | (@user) | daje ciastko dla osoby |
|!dclookup / !dc | | użyj dclookup na sobie |
|!emoji | | link to listy z emotikonami|
|!eta | | pokazuje za ile będziesz DJ |
|!ghostbuster | @user | sprawdza czy osoba ghostuje |
|!gif | (message) | wkleja randomowy gif, możesz również dodać tag, aby szukał gifów w danym zakresie  |
|!help | | linkuje do obrazku pomagającego osobą z pierwszą stycznością z plugiem |
|!join | | dołącz do rulette jeśli jest włączona |
|!leave | | opuść rulette jeśli jest włączona |
|!link | | daje link do obecnie odtwarzanej muzyki |
|!banned | | linkuje listę z zbanowanymi nutami |
|!ping | | pong! |
|!rules | | linkuje do zasad na plugu |

