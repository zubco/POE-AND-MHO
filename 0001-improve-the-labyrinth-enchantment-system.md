# Improve the Labyrinth enchantment system 

## Introduction

Path of Exile has an overwhelming number of enchantments that logically will increase over time. Being early in league or playing in SSF, some player's builds are unplayable or at least not practical without specific enchant/s. Gated game-play possibilities leads to a negative experience of the players interacting with this systems.

## Motivation

Currently in the game we have:
* 1002 helmet enchants (~500 distinct over 2 difficulties)
* 60 glove enchants (15 distinct over 4 difficulties)
* 45 boot enchants (15 distinct over 3 difficulties)

This numbers logically will increase with every league with introduction on new skill gems. Respectively decreasing the chance for the player of getting any useful enchant for his character's build.
If a game system is not providing the player anymore with power it was meant to and becoming a chore the player should trade for (if has the possibility), should be a strong motivation that current enchantment system requires a rework.

## Proposed solution

Extend the crafting bench available in the player's hideout to support enchantments. For enchantment beside item (helmet / glove / boot) it will require a/multiple **Divine token/s**.
For each enchant difficulty variation will be a corresponding difficulty variation of Divine token.
To make over sources of Divine tokens viable, powerful **Eternal** enchantments could require more than 1 Divine token for respective difficulty.

With this new way of enchantment, current **Divine Font** use can appear not that much of reward anymore.
But making the enchant **readable** before use would grant an increased value to the finding. Even if the player currently doesn't need the enchant for his current build, the possibility to decide the item base he enchants lets Divine Font to remain quite useful for a free Labyrinth bonus it represents now.

## Detailed design

### Divine token/s
Consumable currency item that drops from final Izaro encounter in the Labyrinth, with 4 variations which stand for Normal / Cruel / Merciless / Eternal difficulties.
In order this token to drop the player will need to place a **Challenger coin** at the Labyrinth entrance device, this way making Izaro encounter more challenging.

### Challenger coin

It will represent a new currency with drop restricted to the Labyrinth encounters / chests.
It will work similarly to how Divine Vessel works now in game:
* Izaro deals dd% increased Damage
* Izaro has dd% increased Attack and Cast Speed
* Izaro has dd% increased Life
* Izaro has dd% increased Area of Effect

## Alternatives considered

Instead of adding new Challenger coin currency, it could be used Divine Vessel. But the player can found this confusing because of how this 2 work:
* Fist one used on the Labyrinth entrance as a result obtaining a Divine token used with enchantment bench.
* Second one used on map device as a result obtaining a *'Captured Soul of X boss'* used to unlock respective Pantheon power.
