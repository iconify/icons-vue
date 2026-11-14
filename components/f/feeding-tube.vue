<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jop5rxn0q"/><path class="vkgh2bb5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:feeding-tube" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jop5rxn0q {
  d: path("M7.25 21.5V18C5 16.25 4 14 4 11.5c0-3.75 3-6.75 6.75-6.75c3.5 0 6.25 2.5 6.25 6.25l1.5 3c.25.5-.25 1-.75 1H17v2c0 1-.75 1.75-1.75 1.75H13.5v2.75");
}

.vkgh2bb5d {
  d: path("M17 13.75c-2 0-4.5-.25-6.25-1.5c-1.5-1-2.25-2.25-2.25-4m3 2.75l1.5 2.5");
}

</style>
