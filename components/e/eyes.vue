<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gakbbnkrz"/><path class="n0sda9mlv"/><linearGradient id="SVGXpriXcHe" x1="22.523" x2="22.523" y1="46.676" y2="82.083" gradientUnits="userSpaceOnUse"><stop offset="0" class="a72as_i6q"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGXpriXcHe)" class="t9rt76bua"/><ellipse class="db4ex3bwv"/><path class="po-878bfs"/><path class="lj_2um0ym"/><linearGradient id="SVGfIw6TdLx" x1="82.209" x2="82.209" y1="46.676" y2="82.083" gradientUnits="userSpaceOnUse"><stop offset="0" class="a72as_i6q"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGfIw6TdLx)" class="eida76ffe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:eyes" /></template>
<style>
.a72as_i6q {
  stop-color: var(--svg-color--424242, #424242);
}

.db4ex3bwv {
  cx: 93.84px;
  cy: 64px;
  fill: var(--svg-color--eee, #eee);
  rx: 29.97px;
  ry: 44.51px;
}

.eida76ffe {
  d: path("M85.31 59.84c-2.7-2.54-2.1-7.58 1.36-11.26c.18-.19.36-.37.55-.54c-1.54-.87-3.23-1.36-5.01-1.36c-7.19 0-13.02 7.93-13.02 17.7s5.83 17.7 13.02 17.7s13.02-7.93 13.02-17.7c0-1.75-.19-3.45-.54-5.05c-3.23 2.33-7.11 2.64-9.38.51");
}

.gakbbnkrz {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M34.16 106.51C18.73 106.51 6.19 87.44 6.19 64s12.55-42.51 27.97-42.51S62.13 40.56 62.13 64s-12.55 42.51-27.97 42.51");
}

.lj_2um0ym {
  fill: var(--svg-color--b0bec5, #b0bec5);
  d: path("M93.84 23.49c6.63 0 12.98 4 17.87 11.27c5.22 7.75 8.1 18.14 8.1 29.24s-2.88 21.49-8.1 29.24c-4.89 7.27-11.24 11.27-17.87 11.27s-12.98-4-17.87-11.27c-5.22-7.75-8.1-18.14-8.1-29.24s2.88-21.49 8.1-29.24c4.89-7.27 11.24-11.27 17.87-11.27m0-4c-16.55 0-29.97 19.93-29.97 44.51s13.42 44.51 29.97 44.51S123.81 88.58 123.81 64s-13.42-44.51-29.97-44.51");
}

.n0sda9mlv {
  fill: var(--svg-color--b0bec5, #b0bec5);
  d: path("M34.16 23.49c6.63 0 12.98 4 17.87 11.27c5.22 7.75 8.1 18.14 8.1 29.24s-2.88 21.49-8.1 29.24c-4.89 7.27-11.24 11.27-17.87 11.27s-12.98-4-17.87-11.27C11.06 85.49 8.19 75.1 8.19 64s2.88-21.49 8.1-29.24c4.89-7.27 11.23-11.27 17.87-11.27m0-4C17.61 19.49 4.19 39.42 4.19 64s13.42 44.51 29.97 44.51S64.13 88.58 64.13 64S50.71 19.49 34.16 19.49");
}

.po-878bfs {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M93.84 106.51c-15.42 0-27.97-19.07-27.97-42.51s12.55-42.51 27.97-42.51S121.81 40.56 121.81 64s-12.54 42.51-27.97 42.51");
}

.t9rt76bua {
  d: path("M25.63 59.84c-2.7-2.54-2.1-7.58 1.36-11.26c.18-.19.36-.37.55-.54c-1.54-.87-3.23-1.36-5.01-1.36c-7.19 0-13.02 7.93-13.02 17.7s5.83 17.7 13.02 17.7s13.02-7.93 13.02-17.7c0-1.75-.19-3.45-.54-5.05c-3.24 2.33-7.11 2.64-9.38.51");
}

.wk_lp_wlk {
  stop-color: var(--svg-color--212121, #212121);
}

</style>
