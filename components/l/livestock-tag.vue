<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n7-ag4brk"/><path class="dkl9wcaju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:livestock-tag" /></template>
<style>
.dkl9wcaju {
  d: path("M10.75 11.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n7-ag4brk {
  d: path("M10.25 7.5V5.25a1.75 1.75 0 0 1 3.5 0V7.5M5.5 9A1.5 1.5 0 0 1 7 7.5h10A1.5 1.5 0 0 1 18.5 9v5.25c0 3.75-2.75 6.25-6.5 7c-3.75-.75-6.5-3.25-6.5-7Z");
}

</style>
