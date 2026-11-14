<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ig-9r-7zm"/><path class="f_6h9wcig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electoral-votes" /></template>
<style>
.f_6h9wcig {
  d: path("m9.75 7.5l1.75 1.75l2.75-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ig-9r-7zm {
  d: path("M6.5 12h11a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 18v-2.5A3.5 3.5 0 0 1 6.5 12m1 0V3.5a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1V12");
}

</style>
