<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="z5-q_d92g"/><path class="hjnn2590o"/><path class="kdt-km19y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:junction-box-sharp" /></template>
<style>
.hjnn2590o {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 8.5h.01m6.99 7h.01");
}

.kdt-km19y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.25v-2.5m0 16v2.5M5.25 12h-2.5m16 0h2.5M12.9 8.75l-2 3.25h2.25l-2 3.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.z5-q_d92g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 5.25h13.5v13.5H5.25z");
}

</style>
