<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzlgw2-6z"/><path class="p4mexcbhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flask-florence" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p4mexcbhg {
  d: path("M5.25 16Q8.5 14 12 16t6.75 0");
}

.xzlgw2-6z {
  d: path("M10 3v4.75a7 7 0 1 0 4 0V3M8.75 3h6.5");
}

</style>
