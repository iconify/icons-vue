<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ub6dg8blg"/><path class="dzo-c2hxo"/><path class="n1_ff5b8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deforestation-stump" /></template>
<style>
.dzo-c2hxo {
  d: path("M5 7.5v10q0 1.5-1.5 3h17Q19 19 19 17.5v-10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n1_ff5b8l {
  d: path("M9 7.5a3 1 0 1 0 6 0a3 1 0 1 0-6 0");
}

.ub6dg8blg {
  d: path("M5 7.5a7 3.5 0 1 0 14 0a7 3.5 0 1 0-14 0");
}

</style>
