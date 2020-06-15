# M300-Services
M300 Services of Yannick Leutwiler


# Übersicht
- [1. Umgebung auf eigenenm Notebook eingerichtet und funktionsfähig](#1-umgebung-auf-eigenem-notebook-eingerichtet-und-funktionsfähig)
- [2. Eigene Lernumgebung ist eingerichtet](#2-eigene-lernumgebung-ist-eingerichtet)
- [3. Vagrant](#3-vagrant)
- [4. Sicherheitsaspekte sind implementiert](#4-sicherheitsaspekte-sind-implementiert)
- [5. Zusätzliche Bewertungspunkte](#5-zusätzliche-bewertungspunkte)


## 1. Umgebung auf eigenenm Notebook eingerichtet und funktionsfähig
- [x] [1. VirtualBox](#1-virtualbox)
- [x] [2. Vagrant](#2-vagrant)
- [x] [3. Git-client](#3-git-client)
- [x] [4. SSH-key](#4-ssh-key)
- [x] [5. VisualStudio-Code](#5-visualstudio-code)

 
### 1. Virtualbox
Die Software VirtualBox habe ich bereits von den vorherigen Modulen gekannt und davon gebauch gemacht, aus diesem Grund musste ich die Software nicht 
mehr installieren.

![](https://github.com/yck-l/M300-Services/blob/master/00-Images/virtualbox.png "Virtualbox")


### 2. Vagrant
Vagrant war für mich persönlich etwas neues und ich musste die Software installieren. Es ist sehr spannend mit Vagrant zu arbeiten und mithilfe eines Vagrantfiles die VM zu konfigurieren.

![](https://github.com/yck-l/M300-Services/blob/master/00-Images/vagrant.png "Vagrant")

### 3. Git-Client
Der Git-Client hatte ich schon vor diesem Modul gebraucht und musste diesen auch nicht nochmals installieren.

![](https://github.com/yck-l/M300-Services/blob/master/00-Images/gitclient.png "Git-Client")


### 4. SSH-Key
Um du beweisen, dass mein SSH-Key erstellt wurde und funktioniert, habe ich den Befehl ```ssh -v git@github.com``` ausgeführt. Im Screenshot kann man
nachvollziehen, dass ich mich erfolgreich via ssh verbinden konnte.

![](https://github.com/yck-l/M300-Services/blob/master/00-Images/sshkey.png "SSH-Key")


### 5. VisualStudio-Code
Visual Studio hatte ich schon länger auf meinem Rechner, jedoch musste ich noch die 3 folgenden Extensions hinzufügen:

- "Markdown All in One" von Yu Zhang
- "Vagrant Extension" von Marco Stanzi
- "vscode-pdf Extension" von tomiko1207



## 2. Eigene Lernumgebung ist eingerichtet
- [x] [1. GitHub oder Gitlab-Account ist erstellt](#1-github-oder-gitlab-account-ist-erstellt)
- [x] [2. Git-Client wurde verwendet](#2-git-client-wurde-verwendet)
- [x] [3. Dokumentation ist als Markdown vorhanden](#3-dokumentation-ist-als-markdown-vorhanden)
- [x] [4. Markdown-Editor ausgewählt und eingerichtet](#4-markdown-editor-ausgewählt-und-eingerichtet)
- [x] [5. Markdown ist strukturiert](#5-markdown-ist-strukturiert)
- [x] [6. Persönlicher Wissensstand ist Dokumentiert](#6-persönlicher-wissensstand-ist-dokumentiert)


### 1. GitHub oder Gitlab-Account ist erstellt
Der Github Account wurde erstellt. Mein Profil ist unter dem folgenden Link aufrufbar: ![Github yck-l](https://github.com/yck-l)


### 2. Git-Client wurde verwendet
Wie vorhin kurz erwähnt habe ich den Git-Client schon bereits vor diesem Modul benützt. Aus diesem Grund musste ich den Git-Client
nicht mehr herunterladen und habe bereits Erfahrungen mit der Gitbash gesammelt.


### 3. Dokumentation ist als Markdown vorhanden
Die Dokumentation wurde mittels MArkdown geschrieben, wie man auch anhand der Datei (readme.md) nachvollziehen kann.


### 4. Markdown-Editor ausgewählt und eingerichtet
Als Makdown-Editor habe ich mich für VisualStudio-Code mit der Markdown All in One extenion von Yu Zhang entschieden.


### 5. Markdown ist strukturiert
Das MArkdown habe ich mithilfe des LB-Bewertungsrasters erstellt. Ich versuchte die Kriterien nachvollziehbar aufzuteilen und zu dokumentieren.


### 6. Persönlicher Wissensstand ist Dokumentiert
### Linux
Im Bereich Linux kenne ich mich sehr gut aus, da im auf der Arbeit auch in einem Linux Team arbeite. Somit war Linux kein grosses Problem für mich. Ich arbeite sehr gerne mit Linux und kannte die Befehle, welche wir brauchten auch schon. 


### Virtualisierung
Da wir vor zwei Monaten der Virtualisierungs-ÜK hatten, wusste ich auch in diesem Themen-Bereich einiges. Jedoch hat es nicht geschadet das ganze nochmals anzuschauen und das Thema aufzufrischen.


### Vagrant
Mit Vagrant habe ich bis jetzt noch nie gearbeitet. Es war eine völlig neue Erfahrung und es war cool zu sehen, was man damit alles machen und erreichen kann. Ob die Befehle oder die Strukturierung des Vagarant-Files, ich musste alles erstmals anschauen und lernen. 


### Git
Git war nichts neues für mich, da wir auf der Arbeit Bitbucket verwenden. Somit kannte ich die Arbeit mit den Branches etc. schon und konnte mich auf andere Punkte der Arbeit konzentrieren.


### Markdown
Hab ich schon Mal gehört aber noch nie damit gearbeitet, dies waren meine Gedanken als ich dies beim Modul Start gehört habe und dies war auch so. Somit war auch dies eine komplett neue Erfahrung für mich und es war spannend zu sehen, was man alles machen und Dokumentieren kann. Es war für mich Anfangs ein wenig Schwierig, da ich die Formatierungen etc. nicht kannte, mit einem Cheat-Sheet war das ganze jedoch schon viel einfacher.


### Systemsicherheit
Systemsicherheit ist ein sehr breites und spannendes Thema, deshalb will ich nicht behaupten, dass ich das ganze schon kann respektive alles wusste. Doch die Systemsicherheit wird praktisch in jedem Informatik-Modul angesprochen und behandelt, da es ein sehr wichtiger Komponenten ist. Was dieses Modul bis jetzt betrifft würde ich sagen, dass ich die Systemsicherheit schon kannte



## 3. Vagrant
- [x] [1. Bestehende vm aus Vagrant-Cloud einrichten](#1-bestehende-vm-aus-vagrant-cloud-einrichten)
- [x] [2. Kennt die Vagrant-Befehle](#2-kennt-die-vagrant-befehle)
- [x] [3. Eingerichtete Umgebung ist dokumentiert](#3-eingerichtete-umgebung-ist-dokumentiert)
- [x] [4. Funktionsweise getestet inkl. Dokumentation der Testfälle](#4-funktionsweise-getestet-inkl-dokumentation-der-testfälle)
- [x] [5. andere, vorgefertigte vm auf eigenem Notebook aufgesetzt](#5-andere-vorgefertigte-vm-auf-eigenem-notebook-aufgesetzt)
- [x] [6. Projekt mit Git und Mark Down dokumentiert](#6-projekt-mit-git-und-mark-down-dokumentiert)


### 1. Bestehende vm aus Vagrant-Cloud einrichten
Eine bereits erstellte VM kann aus dem Directory, indem das Vagrant File liegt gestartet werden. Es muss jeglich in der Git-Bash zum Verzeichnis gesteuert werden, danach kann mann mit dem Befehl ```vagrant up``` die Virtuelle-Maschine starten.


### 2. Kennt die Vagrant-Befehle
In der untenstehenden Tabelle finden Sie die wichtigsten Vagrant Befehle.

Befehl            | Funktion
----------------- | -------------
`vagrant up`	  | Startet vagrant Umgebung
`vagrant resume`  | Setzt eine suspendierte Maschine fort.
`vagrant reload`  | Startet die VM neu, liest das Config File neu ein
`vagrant ssh`     | Verbinden zu einer Maschine via SSH
`vagrant halt`    | Stopt die vagrant Maschine
`vagrant suspend` | suspendiert eine VM
`vagrant destroy` | Stopt und löscht die gesamte VM
`vagrant -v`      | Zeigt die vagrant Version an
`vagrant status`  | Gibt den Stataus einer VM aus.


### 3. Eingerichtete Umgebung ist dokumentiert
Wir haben die folgenden Services in der Umbgebung der LB02 eingerichtet:

- Apache2 Webserver installiert
- UFW Firewall installiert und Regeln erstellt
- Reverse-Proxy konfiguriert
- Benutzer und Gruppen erstellt und Rechte verteilt
- LDAP installiert und konfiguriert
- HTTPS freigeschaltet


### Netzwerkplan
![](https://github.com/yck-l/M300-Services/blob/master/00-Images/netzwerkplan.png "Netzwerkplan")


### 4. Funktionsweise getestet inkl. Dokumentation der Testfälle
Unten können Sie unsere Testfälle sehen. Wir haben die verschiedenen Services auf unserer VM getestet und überprüft.

#### Testfälle:
| Testfall: 001     | Apache2 Webserver installation                                                     |
| ----------------- | ---------------------------------------------------------------------------------- |
| Ziel:             | Der Apache2 Webserver wurde korrekt installiert.                                   |
| Beschreibung:     | Mit dem Befehl "sudo service apache2 status" den Status des Servers überprüfen.    |
| Soll-Wert:        | service apache2 is running.                                                        |
| Ist-Wert:         | service apach2 is running.                                                         |
| Analyse:          | OK                                                                                 |
| Weitere Schritte: | -                                                                                  |

| Testfall: 002     | LDAP korrekt installiert                                                           |
| ----------------- | ---------------------------------------------------------------------------------- |
| Ziel:             | LDAP wurde richtig installiert.                                                    |
| Beschreibung:     | Web-GUI von LDAP ist aufrufbar.                                                    |
| Soll-Wert:        | LDAP-GUI kann aufgerufen und es kann eingeloggt werden.                            |
| Ist-Wert:         | LDAP-GUI kann aufgerufen und es kann eingeloggt werden.                            |
| Analyse:          | OK                                                                                 |
| Weitere Schritte: | -                                                                                  |

| Testfall: 003     | Benutzer ist korrekt der Gruppe zugewiesen.                                                  |
| ----------------- | ----------------------------------------------------------------------------------           |
| Ziel:             | Benutzer ist korrekt der Gruppe zugewiesen.                                                  |
| Beschreibung:     | mit dem Befehl "cat /etc/group" werden die Gruppen und die dazugehörigen Benutzer angezeigt. |
| Soll-Wert:        | database:db-admin / website:web-admin                                                        |
| Ist-Wert:         | database:db-admin / website:web-admin                                                        |
| Analyse:          | OK                                                                                           |
| Weitere Schritte: | -                                                                                            | 


### 5. andere, vorgefertigte vm auf eigenem Notebook aufgesetzt
Ich habe noch andere Virtuelle Maschinen mithilfe von Vagrant auf meinem Notebook aufgesetzt. Das Vagrantfile finden Sie under dem folgenden Link:

![](https://github.com/yck-l/M300-Services/blob/master/01-Vagrantfiles/)

### 6. Projekt mit Git und Mark Down dokumentiert
Wie vorhin schon angesprochen kann man anhand der Readme.md Datei erkennen, dass ich die Doku mit Markdown verfasst habe.


## 4. Sicherheitsaspekte sind implementiert
- [x] [1. Firewall eingerichtet inkl. Rules](#1-firewall-eingerichtet-inkl-rules)
- [x] [2. Reverse-Proxy eingerichtet](#2-reverse-proxy-eingerichtet)
- [x] [3. Benutzer- und Rechtevergabe ist eingerichtet](#3-benutzer--und-rechtevergabe-ist-eingerichtet)
- [x] [4. Sicherheitsmassnahmen sind dokumentiert](#4-sicherheitsmassnahmen-sind-dokumentiert)
- [x] [5. Projekt mit Git und Mark Down dokumentiert](#5-projekt-mit-git-und-mark-down-dokumentiert)


### 1. Firewall eingerichtet inkl. Rules
Auf dem untenstehenden Screenshot, wird der aktuelle UFW-Firewall Status angezeigt. Anhand des Screenshots kann man ebenfalls die Konfiguration nachvollziehen.

![](https://github.com/yck-l/M300-Services/blob/master/00-Images/ufwstatus.png "UFW-Status")

### 2. Reverse-Proxy eingerichtet
Im folgenden Screenshot können sie unsere Proxy-Konfiguration begutachten, welche auch im Script zu sehen ist.

![](https://github.com/yck-l/M300-Services/blob/master/00-Images/proxyconfig.png "Proxy-config")

### 3. Benutzer- und Rechtevergabe ist eingerichtet
Im Screenshot können sie die erstellten Benutzer, Gruppen und deren Zugehörigkeit sehen.

![](https://github.com/yck-l/M300-Services/blob/master/00-Images/usergroups.png "User and Groups")

### 4. Sicherheitsmassnahmen sind dokumentiert
Die Sicherheitsmasnahmen welche wir für unsere Umgebung vorgenommen haben wir einerseit im Vagrantfile anhand von Kommentaren Dokumentiert, andererseit können Sie die Sicherheitsmassnahmen unten nochmnals sehen.

- Firewall aktiviert
- Dazugehörige Firewall Rules erstellt
- Proxy installiert und konfiguriert
- Reverse Proxy Konfiguriert


### 5. Projekt mit Git und Markdown dokumentiert
Wie vorhin schon angesprochen kann man anhand der Readme.md Datei erkennen, dass ich die Doku mit Markdown verfasst habe.



## 5. Zusätzliche Bewertungspunkte
- [x] [1. Vergleich Vorwissen - Wissenszuwachs](#1-vergleich-vorwissen---wissenszuwachs)
- [x] [2. Reflexion](#2-reflexion)


### 1. Vergleich Vorwissen - Wissenszuwachs
Was Vagrant angeht, hatte ich persönlich kein Vorwissen und musste alles neu dazu lernen. Da ich jedoch schon viel mit YAML gearbeitet habe war es mit dem Vagrant-File ein wenig einfacher. Ich habe sehr viel Wissenszuwachs durch dieses Modul ergattert, wir haben zu dritt ein Vagrantfile mit ca 115 Zeilen Code erstellt.


### 2. Reflexion
Die LB02 hat mir sehr viel Spass bereitet und ich köonnte sehr viel lernen. Anfangs war es ein wenig kompliziert, da ich keinerlei Erfahrungen mit Vagrant hatte. Durch dies war es am anfangs auch ein wenig komisch mit den Befehlen, welche ich mir aber ziemlich schnell merken konnte. Wir konnten sehr viel in dieser LB dazu lernen und haben und unser Wissen erweitern.