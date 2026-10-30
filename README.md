# Echo Defense — prototype

Extremely simple playable prototype of a mobile tower-defense concept by **Schwarze Spiele** (Concept Brief v0.9).

**Play:** https://zacharyryanschwartz-droid.github.io/echo-defense/  (add `?fast=3` for 3x speed, `?fast=N` for N x)

One tower in the center, attacked from 8 sides over 5 rounds (hordes of 40/50/60/70/80).
Build walls and turrets once; between rounds you get 3 patches, 2 turret moves, and can move 2 armies.
The horde learns by rumor: creatures that break a defense get a yellow ring and tell neighbours within ~2 tiles;
survivors carry it into the next round. Move a turret onto a known gap to make the rumor stale.

Single self-contained `index.html` (vanilla JS + canvas, no build step).
The previous 3-lane prototype is kept at [`old-lanes.html`](https://zacharyryanschwartz-droid.github.io/echo-defense/old-lanes.html).
