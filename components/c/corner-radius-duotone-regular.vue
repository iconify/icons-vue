<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p33184bqk"/><path class="e25empizl"/><path class="blvi9lblf"/><path class="esvf46wxs"/><path class="s-etibjpa"/><path class="ben7bq53u"/><path class="xr2p35g3w"/><path class="kr1cz4b8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-radius-duotone-regular" /></template>
<style>
.ben7bq53u {
  d: path("M4 10a6 6 0 0 1 6 -6");
}

.blvi9lblf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 10a6 6 0 0 1 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e25empizl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.esvf46wxs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 4h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kr1cz4b8j {
  d: path("M9 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p33184bqk {
  fill: currentColor;
  d: path("M9 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s-etibjpa {
  d: path("M4 10v10");
}

.xr2p35g3w {
  d: path("M10 4h10");
}

</style>
