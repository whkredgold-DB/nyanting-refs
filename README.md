# Nyanting in Trouble — locked character references

Static image hosting for the locked character reference sheet. These four files
are fed to image and video generators as reference inputs, so their URLs must
stay stable and their bytes must never change.

**Do not edit, rename, re-compress, or replace these files.** Changing one
changes the character across everything generated afterwards. If the design ever
changes, add a `-v2` file alongside and leave `-v1` in place.

## Current — v2

| File | View |
|---|---|
| `nyanting-front-LOCKED-v2.png` | **Master.** Front |
| `nyanting-3q-LOCKED-v2.png` | Three-quarter |
| `nyanting-side-LOCKED-v2.png` | Side profile |
| `nyanting-back-LOCKED-v2.png` | Back |

## Superseded — v1

Kept deliberately. **Do not delete.** v1 had no mouth; v2 adds a small closed
smile. The `-v1` files are what the first expression plate set was generated
from, and removing them would erase that lineage.

| File | View |
|---|---|
| `nyanting-front-LOCKED-v1.png` | Front |
| `nyanting-3q-LOCKED-v1.png` | Three-quarter |
| `nyanting-side-LOCKED-v1.png` | Side profile |
| `nyanting-back-LOCKED-v1.png` | Back |

All 1024x1024 PNG.

## Expression plates

`expressions/` holds the eight expression plates plus a contact sheet. Feed the
relevant plate alongside the master when generating a shot that needs a specific
expression. `expression-sheet.png` is a human index, not a generator input.

Her expressions run on **ears and tail**, both of which read in silhouette.
`nyanting-expr-04-alarm.png` is the only plate where her eyes depart from solid
dusty blue - it is the rare explosive state, at most once per video.

## The kitchen set

`kitchen/nyanting-kitchen-LOCKED-v1.png` is the locked location. Pass it as a
second `image_input` alongside the character (or an expression plate) on every
shot set in the kitchen, and name explicitly what must be reproduced - the
reference steers, it does not guarantee.

**The character must be scaled against named objects in the room, every time.**
She is meant to be too big for it, and that relationship is not encoded in
either reference. Adjectives like "slightly too big" get ignored; measurements
like "the counter is level with her chest" get obeyed.
