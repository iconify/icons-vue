<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mo8xc3blj"/><path class="zom6fac5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-balloon-pair" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mo8xc3blj {
  d: path("M10 17c-4.5-3.25-7.5-6-7.5-9.25c0-2.5 2-4.25 4.25-4.25c1.5 0 2.75.75 3.25 1.75c.5-1 1.75-1.75 3.25-1.75c2.25 0 4.25 1.75 4.25 4.25c0 3.25-3 6-7.5 9.25");
}

.zom6fac5x {
  fill: currentColor;
  d: path("M15.5 20.5c-3-2.25-5-4.25-5-6.75c0-1.75 1.25-3.25 3-3.25c1 0 1.75.5 2 1.25c.25-.75 1-1.25 2-1.25c1.75 0 3 1.5 3 3.25c0 2.5-2 4.5-5 6.75");
}

</style>
