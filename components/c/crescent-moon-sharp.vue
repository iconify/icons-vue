<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vf68mg0yd"/><path class="y-kzbdbkl"/><path class="ki91mbbtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crescent-moon-sharp" /></template>
<style>
.ki91mbbtt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 9.5l.3 2.2L8 12l-2.2.3l-.3 2.2l-.3-2.2L3 12l2.2-.3z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vf68mg0yd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.25a9.25 9.25 0 1 1 0 17.5a10.08 10.08 0 0 0 0-17.5Z");
}

.y-kzbdbkl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 9h.01m-.76 6h.01");
}

</style>
