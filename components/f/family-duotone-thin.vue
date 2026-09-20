<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y4l98q7pn"/><path class="fm8lsfbkn"/><path class="cljv9cb7j"/><path class="k74vnib1e"/><path class="clbajiboq"/><path class="ptubxntjf"/><path class="bqfthgbev"/><path class="l7lvdwbxu"/><path class="sb0fpuinl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:family-duotone-thin" /></template>
<style>
.bqfthgbev {
  d: path("M14 15a4 4 0 0 1 8 0");
}

.clbajiboq {
  d: path("M2 15a4 4 0 0 1 8 0");
}

.cljv9cb7j {
  fill: currentColor;
  d: path("M10 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fm8lsfbkn {
  fill: currentColor;
  d: path("M15 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k74vnib1e {
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.l7lvdwbxu {
  d: path("M10 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ptubxntjf {
  d: path("M15 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.sb0fpuinl {
  d: path("M9 19a3 3 0 0 1 6 0");
}

.y4l98q7pn {
  fill: currentColor;
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
