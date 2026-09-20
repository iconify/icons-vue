<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGg4Dp1cXp)" class="r4i437pya"/><path class="vnxs7ebnb"/><path class="ok3dcrbfh"/></g><defs><linearGradient id="SVGg4Dp1cXp" x1="16.003" x2="13.714" y1="6.582" y2="19.42" gradientUnits="userSpaceOnUse"><stop class="niyiqjple"/><stop offset="1" class="q67t54x_p"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bsw-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.niyiqjple {
  stop-color: var(--svg-color--ff496a, #ff496a);
}

.ok3dcrbfh {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.108 10.832c.615-1.33.395-1.336.86-2.587a1.795 1.795 0 0 1 1.791-1.24c.46 0 .94.145 1.146.17c.835.115 1.05-.185 2.816-.465l.25-.035A8 8 0 0 0 4.78 8.56c2.647.65 5.498 2.076 6.329 2.27M9.357 5.404c.235.035 1.366 1.436 1.576 5.043c0 0-1.451-.35-1.766-1.101c-.255-.61.08-1.42.19-3.942m8.905 1.6l.014.016l-.064-.005c.02-.01.035-.01.05-.01M4.004 12.009c0-.64.075-1.261.215-1.851q.435.359.93.815c2.087 1.93 5.478 3.457 6.714 2.041h.005c-.225.3-1.04 1.17-2.686.875L6.53 17.845a7.98 7.98 0 0 1-2.526-5.837");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q67t54x_p {
  stop-color: var(--svg-color--e42648, #e42648);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vnxs7ebnb {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.211 7.016c-.56.11-1.085.265-1.52.36a2.72 2.72 0 0 0-2.132 2.381c-.18 1.246.24 1.781.055 3.232c-.32 2.526-2.751 3.402-3.882 3.927c-.65.3-2.246 1-3.472 1.536A8.005 8.005 0 0 0 18.266 7.026l-.06-.01z");
}

</style>
