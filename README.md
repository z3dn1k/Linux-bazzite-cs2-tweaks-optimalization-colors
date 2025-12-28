# Linux Bazzite CS2 Increased Vibrance

Some terminal magic and launch option buffoonery to make CS2 more vibrant on Bazzite Linux.

## Launch Options
Add this to your CS2 Launch Options in Steam:

```Launch options
gamescope -w 1080 -h 1080 -W 1920 -H 1080 -r 320 -S stretch -f --force-grab-cursor -- env ENABLE_VKBASALT=1 %command% -high -novid -fullscreen
```

### Warning and potentional problems
1. -r 320 --> makes refresh rate 320hz so you need a monitor with 320hz to use this but of course you can change it to your own refresh rate 60hz, 144hz, 240hz or whatever you have
2. gamescope -w 1080 -h 1080 --> makes a custom resolution and starts with it for me i use 1080x1080 (dont judge pls) you can either change it or remove it
3. all the launch options --> honestly the most important thing is to follow the tutorial and read this so you change whats needed
