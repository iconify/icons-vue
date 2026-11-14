<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eef6du3qc"/><path class="ujlu0fcjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gorilla-face" /></template>
<style>
.eef6du3qc {
  d: path("M6.5 9C6.5 5 9 3 12 3s5.5 2 5.5 6c1.5 2 2 5 1.5 7.5c-.5 3-3.5 4.5-7 4.5s-6.5-1.5-7-4.5C4.5 14 5 11 6.5 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ujlu0fcjn {
  d: path("M5.5 10.75c-2.75 0-2.75 4.5-.5 4.5m13.5-4.5c2.75 0 2.75 4.5.5 4.5m-10.75-4.5Q10 8.5 12 10q2-1.5 3.75.75M9.5 14q2.5-1.25 5 0q.75 2.75-2.5 2.75T9.5 14");
}

</style>
