# MG3
## Devlog


1. The default values are 0 for float, 0 for int, false for bool, and null for string.


2.  The Update() method is automatically called in every frame. In minigame3, Update() is used to subtract Time.deltaTime from the timer every frame. We do not need to call it in other ways.


3. The KickWeapon class uses a Timer component to control the duration of the kick. When ActivateKick() is called, the initial time of the timer is _lifetimeSeconds. The Update() method checks whether the timer has finished by calling IsFinished() in every frame. Once the timer runs out, the kick's GameObject is disactivated.


## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)