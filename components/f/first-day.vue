<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j3a6q74-d"/><path class="ehl-4jbon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:first-day" /></template>
<style>
.ehl-4jbon {
  d: path("M20.5 16.5h-3A1.5 1.5 0 0 0 16 18v3m-6.5-8l3-1.5v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3a6q74-d {
  d: path("M6 4.5h12A2.5 2.5 0 0 1 20.5 7v9.5L16 21H6a2.5 2.5 0 0 1-2.5-2.5V7A2.5 2.5 0 0 1 6 4.5m2.25-2v4m7.5-4v4");
}

</style>
