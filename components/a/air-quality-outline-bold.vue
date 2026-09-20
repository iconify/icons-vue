<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="oqr7qbc2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:air-quality-outline-bold" /></template>
<style>
.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.oqr7qbc2i {
  d: path("M9 13a5 5 0 0 1 7 -5 5 5 0 0 1 -7 5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
