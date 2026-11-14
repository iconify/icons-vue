<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j_q_y1bdx"/><path class="ijga2w9th"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:load-curve" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ijga2w9th {
  d: path("M7 16c1.5 0 2-6 3.75-6s1.75 3.5 3.5 3.5S16.5 7 20.5 7");
}

.j_q_y1bdx {
  d: path("M3.5 3.5v17h17");
}

</style>
