# WoW Forever Combat Rogue Gameplay Sim

A browser sim for practising the level 60 Combat (dagger Backstab) Rogue rotation in World of Warcraft: Forever. You press the abilities; the sim auto-attacks a raid boss dummy with both weapons, tracks Energy, Combo Points and cooldowns, and shows a damage breakdown when the dummy dies.

**Play it:** https://wowf-gameplay.github.io/rogue-gameplay-sim/

## Features

- Backstab, Slice and Dice, Eviscerate, Blade Flurry, Adrenaline Rush and Thistle Tea
- Continuous Energy regeneration, Combo Points with Puncturing Wounds, Ruthlessness and Relentless Strikes
- Instant Poison on the main hand, stacking Deadly Poison on the off hand, Windfury Totem, Crusader and Shadowcraft set procs
- Toggles for raid buffs, consumables and boss debuffs
- Gear and talent tabs, plus a Stats tab for entering your own character stats
- Rebindable keys (with Shift/Ctrl), adjustable dummy health, and a Warcraft Logs-style end-of-fight breakdown

## Setup

The default gear, enchants, poisons and 17/32/2 talent build follow the [MythicSim](https://mythicsim.com/wow-forever/tier-list) Combat Rogue preset. Mechanics follow the open-source engine MythicSim is built on and Forever beta tooltips, and may change as the beta does.

Two notes on the defaults: Trueshot Aura is part of the MythicSim preset but their engine does not apply it, and Curse of Recklessness is applied here but not there, so with everything on this sim reports a little more damage than the MythicSim figure. Turn both off to compare like for like. Felstriker's crit proc and the Goblin Sapper Charge are not simulated.

## Running locally

It is a single file with no build step: open `index.html` in a browser. Ability icons load from Wowhead's image server, so they need an internet connection.

## Related

- [All sims](https://wowf-gameplay.github.io/)
- [Warrior gameplay sim](https://github.com/wowf-gameplay/warrior-gameplay-sim)
- [Paladin gameplay sim](https://github.com/wowf-gameplay/paladin-gameplay-sim)
- [Shaman gameplay sim](https://github.com/wowf-gameplay/shaman-gameplay-sim)
- [Druid gameplay sim](https://github.com/wowf-gameplay/druid-gameplay-sim)

## Disclaimer

Fan project, not affiliated with Blizzard Entertainment. World of Warcraft is a trademark of Blizzard Entertainment, Inc.
