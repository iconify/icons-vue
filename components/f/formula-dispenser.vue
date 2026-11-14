<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vkii2ub9f"/><path class="yyq6y1b0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:formula-dispenser" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vkii2ub9f {
  d: path("M9.5 9h5a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 6 18v-5.5A3.5 3.5 0 0 1 9.5 9m-3-3h11A1.5 1.5 0 0 1 19 7.5A1.5 1.5 0 0 1 17.5 9h-11A1.5 1.5 0 0 1 5 7.5A1.5 1.5 0 0 1 6.5 6");
}

.yyq6y1b0t {
  d: path("m6.5 3.5l6.5-1h5c0 4.75-5 4.75-5 0");
}

</style>
