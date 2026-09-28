# Governance: Wie wir entscheiden

## Proposal-Lebenszyklus

`proposal` → `voting` → `accepted` / `rejected` → `active` → `done`

1. **Proposal**: Jede:r öffnet einen Issue mit dem Proposal-Template.
2. **Diskussionsphase (3 Tage)**: Fragen klären, Scope schärfen.
3. **Voting (7 Tage)**: Ein Maintainer setzt das Label `voting`.
   - 👍 = dafür, 👎 = dagegen, 🎉 = ich baue mit (zählt zusätzlich als Zusage)
4. **Entscheidung**: Angenommen, wenn
   - mind. **5 👍** und mehr 👍 als 👎, **und**
   - mind. **2 Personen 🎉** mitbauen wollen (kein Projekt ohne Bauleute).
5. **Start**: Ordner `projects/<name>/` aus `_template` anlegen, Lead benennen.

## Regeln

- Pro Person eine Stimme pro Proposal
- Mehrere Projekte dürfen gleichzeitig laufen
- Inaktive Projekte (90 Tage ohne Commit) werden auf `paused` gesetzt
- Änderungen an diesen Regeln laufen selbst als Proposal
- Maintainer sind Moderator:innen, keine Entscheider:innen

## Rollen

- **Contributor**: jede:r
- **Project Lead**: koordiniert ein Subprojekt
- **Maintainer**: pflegt das Gesamtrepo, moderiert Votings
