<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mibtptc1d"/><path class="eyi3spbxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:allergen-mustard" /></template>
<style>
.eyi3spbxl {
  d: path("m7.5 7.5l1-4h1l1 4m2.5-3h.01m4.99 10V18m0 3h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mibtptc1d {
  d: path("M3.5 19.25v-8.116a1.75 1.75 0 0 1 .406-1.121L5.475 8.13A1.75 1.75 0 0 1 6.82 7.5h4.36a1.75 1.75 0 0 1 1.345.63l1.569 1.883a1.75 1.75 0 0 1 .406 1.121v8.116A1.75 1.75 0 0 1 12.75 21h-7.5a1.75 1.75 0 0 1-1.75-1.75");
}

</style>
