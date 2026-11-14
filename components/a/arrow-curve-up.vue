<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o7qzh_bmi"/><path class="re-k1ub6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-curve-up" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o7qzh_bmi {
  d: path("M4 18.5c7.5 0 12-5 12-13.5");
}

.re-k1ub6p {
  d: path("M12.5 8.5L16 5l3.5 3.5");
}

</style>
