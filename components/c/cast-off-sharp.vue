<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="v5x5m9brd"/><path class="qj9faybbb"/><path class="c0954yb2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cast-off-sharp" /></template>
<style>
.c0954yb2f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.25 19.5h.01");
}

.qj9faybbb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.25a7.5 7.5 0 0 1 7.5 7.5m-7.5-3.5h3.5v3.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v5x5m9brd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8V4.25h18.5v15.5h-7.5");
}

</style>
