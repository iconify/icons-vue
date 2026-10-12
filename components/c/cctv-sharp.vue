<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bun9_lbtr"/><path class="hw3g_zuuw"/><path class="x-1fftdvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cctv-sharp" /></template>
<style>
.bun9_lbtr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.11 7.16l11.59-3.1l1.45-.39l.39 1.45l.91 3.38l.39 1.45l-1.45.39l-11.59 3.1l-1.45.39l-.39-1.45L3.05 9l-.39-1.45z");
}

.hw3g_zuuw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 10.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x-1fftdvz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.5 13.25l1 4.25h6.25m0-3.5v7");
}

</style>
