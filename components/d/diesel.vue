<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mi7_5yb0w"/><path class="rzy4jubdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diesel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mi7_5yb0w {
  d: path("M7 3h4.5A3.5 3.5 0 0 1 15 6.5V18a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18V6.5A3.5 3.5 0 0 1 7 3m8 9.5h1.75a1 1 0 0 1 1 1V17a1.5 1.5 0 0 0 3 0V8l-2.5-2.5M6.5 8v8");
}

.rzy4jubdg {
  d: path("M6.5 8H8a4 4 0 0 1 0 8H6.5");
}

</style>
