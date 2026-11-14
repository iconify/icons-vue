<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mqxzn4b3t"/><path class="zhm8o7bno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:earbuds-case-open" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mqxzn4b3t {
  d: path("M4 13h16v2.5a4.5 4.5 0 0 1-4.5 4.5h-7A4.5 4.5 0 0 1 4 15.5Zm1.275-7.787L17.093 3.13a2 2 0 0 1 2.317 1.622a2 2 0 0 1-1.623 2.317L5.97 9.153A2 2 0 0 1 3.653 7.53a2 2 0 0 1 1.622-2.317");
}

.zhm8o7bno {
  d: path("M7.25 13a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m6 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
