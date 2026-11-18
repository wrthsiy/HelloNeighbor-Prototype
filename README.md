# HelloNeighbor

A single-player, first-person exploration game by **Ctrl-C Ctrl-V Studios**.

Search the house and its surrounding yard, find five hidden colored keys, and reach the exit while avoiding the neighbor. For a more playful experience, try Fan mode with a faster, flying neighbor.

**Version:** 1.0.0  
**Platforms:** Windows 64-bit and Android

## Download and install

### Windows

1. Download `HelloNeighbor-Windows-1.0.0.zip`.
2. Extract the entire archive into a folder.
3. Open `HelloNeighbor.exe`.

Keep the executable, `HelloNeighbor_Data`, `MonoBleedingEdge`, and the included DLL files together in the extracted folder.

### Android

1. Download `HelloNeighbor-Android-1.0.0.apk` to your device.
2. Open the APK with Android's package installer.
3. If prompted, allow installation from the app you used to open the APK.
4. Install the game and launch **HelloNeighbor**.

The APK supports ARM64 and ARMv7 devices running Android 5.1 or newer. Play in landscape orientation.

## Starting the game

The Studio splash and loading screen appear before the Main Menu. Loading continues automatically.

Choose an option from the Main Menu:

- **Story mode** — find the keys and reach the exit.
- **Fan mode** — explore with a faster, flying neighbor.
- **Settings** — adjust look sensitivity.
- **Exit** — close the game.

## Controls

### Windows

| Action | Control |
| --- | --- |
| Move forward / backward | W / S |
| Move left / right | A / D |
| Look around | Mouse |
| Sprint | Hold Left Shift while moving |
| Jump | Space |
| Open or close Settings | Esc |
| Select menu options | Left mouse button |

Movement follows the direction you are looking. Opening Settings pauses gameplay and releases the mouse pointer so you can use the menu.

### Android

| Action | Control |
| --- | --- |
| Move | Drag the joystick on the left |
| Look around | Drag on the right side of the screen |
| Sprint | Hold the running button while moving |
| Jump | Tap the jump button |
| Open Settings | Tap the gear button |
| Select menu options | Tap the option |

Use **Continue** in Settings to return to gameplay.

## Story mode

### Your objective

1. Explore the house and the surrounding yard.
2. Find all **five colored keys**. Walk into a key to collect it automatically.
3. Watch the on-screen counter to track your progress.
4. After collecting all five, enter the marked **EXIT** doorway in the house.

The keys are hidden in different places, so search carefully around the building and its furniture. Exact hiding spots are left for you to discover.

Collecting the fifth key unlocks the exit objective. You still need to reach the doorway to finish the level.

### Getting caught

The neighbor can catch you in Story mode. When you are caught, the level restarts and your collected-key progress resets.

### Winning

Reaching the exit after collecting all five keys displays the victory screen. It stays visible for **10 seconds**, then automatically returns you to the Main Menu.

## Fan mode

Fan mode is the game's free-play mode, using the updated house and surrounding area.

- The neighbor is faster and has Fly mode enabled.
- The neighbor is nonlethal and will not end your run.
- There are no key-collection or exit objectives.

Explore at your own pace. Return to the Main Menu through Settings when you are finished.

## Settings and progress

- Use the sensitivity slider to adjust how quickly the view turns.
- Sensitivity is saved automatically for future sessions.
- Opening Settings pauses gameplay.
- Choose **Continue** to resume or **Main Menu** to leave the current level.
- Story key progress belongs to the current attempt. Getting caught, restarting, or leaving the level resets it.

## Closing the game

On Windows, open Settings with **Esc**, return to the Main Menu, and choose **Exit**. On Android, you can also close the game through your device's normal app controls.

## Troubleshooting

- **Windows is missing a game file:** extract the complete ZIP again and keep all included files and folders together.
- **The mouse is moving the camera when you want to use menus:** press **Esc** to open Settings.
- **Looking around feels too fast or too slow:** adjust the sensitivity slider in Settings.
- **The exit has not completed the level:** check that the counter shows all five keys, then enter the marked doorway.
- **Android cannot install the APK:** check that your device has sufficient free space, uses a supported ARM architecture, and allows installation from your chosen installer app.

## Release information

This release includes the Studio splash, custom game icon, Story and Fan modes, updated prop collisions, and keyboard/mouse and touch controls.

The Android APK is release-signed. Physical Android-device testing is still pending; compatibility across all devices has not been confirmed.

**Developed by Ctrl-C Ctrl-V Studios.**
