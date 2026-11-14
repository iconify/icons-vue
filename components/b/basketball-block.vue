<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rg8jim1oj"/><path class="xf8gqgboo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basketball-block" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rg8jim1oj {
  d: path("M3 21.5v-7a1.5 1.5 0 0 1 3 0V17m0 0v-3.5a1.5 1.5 0 0 1 3 0V17m0 0v-2.5a1.5 1.5 0 0 1 3 0V19a2.5 2.5 0 0 1-2.5 2.5m3-14.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m0 0h8");
}

.xf8gqgboo {
  d: path("M14.25 3.75c1.25 1.75 1.25 4.75 0 6.5m4.5-6.5c-1.25 1.75-1.25 4.75 0 6.5m-3.5 3.5q4.25-.5 6.25-2.5m-4.25 5.25q3-.75 4.5-2.25");
}

</style>
