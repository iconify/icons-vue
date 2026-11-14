<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vfq2hmceg"/><path class="vwsbfcbpf"/><path class="ol-q6bbap"/><path class="ppbc35hlr"/><path class="c7jb3vb6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loyalty-progress" /></template>
<style>
.c7jb3vb6a {
  d: path("M8.75 12H10m0 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm2.5 0h1.25");
}

.ol-q6bbap {
  d: path("M5 12h1.25");
}

.ppbc35hlr {
  fill: currentColor;
  d: path("M6.25 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfq2hmceg {
  d: path("m17.75 8.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.vwsbfcbpf {
  fill: currentColor;
  d: path("M2.5 12A1.25 1.25 0 1 0 5 12a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
