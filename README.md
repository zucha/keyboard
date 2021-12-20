# Colemak + apostrophe

Custom keyboard for colemak layout with apostrophe variation (ISO_Level3_Latch)

Create custom keyboard layout  colemak + apastrofs variant

## Commands to set previous settings:

`setxkbmap -layout lv colemak`

`setxkbmap -layout lv apostrophe`

## Export current keyboard maps into plaintext file

`xkbcomp $DISPLAY xkb.dump`

So i exported both colemak and apostrophe layots

`setxkbmap -layout lv colemak; xkbcomp $DISPLAY colemak.dump`

`setxkbmap -layout lv apostrophe;  xkbcomp $DISPLAY apostophe.dump`

## Import custom map

`xkbcomp custom.dump $DISPLAY`

### Some notes

compiled keymap (.xkm)
Need to make ISO_Level3_Latch to colemak