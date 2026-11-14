<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zr8e-k48d"/><path class="dx5y55lqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:live-arrivals" /></template>
<style>
.dx5y55lqk {
  d: path("M16.941 6.916a2.75 2.75 0 0 1 0 5.168");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zr8e-k48d {
  d: path("M6 4h12a3.5 3.5 0 0 1 3.5 3.5V16a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 16V7.5A3.5 3.5 0 0 1 6 4m0 4.5h4M6 13h12M6 16.5h9m1-7h.01");
}

</style>
