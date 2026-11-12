HW46 firmware update - copy these 4 files into your repo (same paths), commit, push.
  build.yaml                                   -> Studio enabled on the LEFT half only
  config/hw46.keymap                           -> new 46-key keymap, 4 layers, F/J hold-Shift, Studio unlock, 2 reserved layers
  config/boards/shields/hw46/hw46.dtsi         -> 46-key matrix transform + physical layout (needed for Studio)
  config/boards/shields/hw46/Kconfig.defconfig -> right half advertises as HW46-R
Wiring used: stacks S1..S7 = 022 024 100 011 104 106 115 (S1 = inner column);
031 = row 1, 002 = row 2, 111 = row 3, 029 = thumb row (same on both halves).
