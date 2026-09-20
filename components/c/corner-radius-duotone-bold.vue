<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p33184bqk"/><path class="e7h5h_hse"/><path class="o56c1b0in"/><path class="b2pi3ybgo"/><path class="s-etibjpa"/><path class="ben7bq53u"/><path class="xr2p35g3w"/><path class="kr1cz4b8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-radius-duotone-bold" /></template>
<style>
.b2pi3ybgo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 4h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ben7bq53u {
  d: path("M4 10a6 6 0 0 1 6 -6");
}

.e7h5h_hse {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kr1cz4b8j {
  d: path("M9 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.o56c1b0in {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 10a6 6 0 0 1 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xr2p35g3w {
  d: path("M10 4h10");
}

</style>
