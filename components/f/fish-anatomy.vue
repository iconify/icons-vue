<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="olky6abwj"/><path class="y8mci8bnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fish-anatomy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.olky6abwj {
  d: path("M3 13.5C6 8 13.5 8 16.5 13.5l4.5-4v8l-4.5-4C13.5 19 6 19 3 13.5");
}

.y8mci8bnv {
  d: path("M9.75 9.5c1.25-3 3.25-4 5.75-4l-2 4.75m-6-.5q2.5 3.75 0 7.5M5.25 13.5h.01");
}

</style>
