# herdr-layout-cli

A square, text-first layout for the Herdr desktop app. Departure Mono at 13, one dark color, no rounding.

![CLI](preview.png)

## Install

Departure Mono is bundled in `fonts/`; no separate install needed. Copy into `~/.config/herdr-app`:

```sh
git clone https://github.com/yych42/herdr-layout-cli /tmp/herdr-layout-cli
cp -R /tmp/herdr-layout-cli/layouts/. ~/.config/herdr-app/layouts/
cp -R /tmp/herdr-layout-cli/themes/.  ~/.config/herdr-app/themes/
cp -R /tmp/herdr-layout-cli/mods/.    ~/.config/herdr-app/mods/
mkdir -p ~/.config/herdr-app/fonts && cp /tmp/herdr-layout-cli/fonts/*.otf ~/.config/herdr-app/fonts/
herdr-app do layout.switch '{"name":"cli"}'
```

## Fonts

[Departure Mono](https://departuremono.com) by Helena Zhang and Tobias Fried, MIT licensed. The license is in `fonts/LICENSE-DepartureMono.txt`.

See `RECIPE.md` for details and limits. Not official.
