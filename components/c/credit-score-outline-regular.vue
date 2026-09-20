<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="x7bkced7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:credit-score-outline-regular" /></template>
<style>
.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x7bkced7s {
  d: path("m12 8 2 2 -2 2 -2 -2Z");
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
