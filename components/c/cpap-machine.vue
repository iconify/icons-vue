<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w5f9tubjt"/><path class="vsv64dsyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cpap-machine" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vsv64dsyy {
  d: path("m18.99 4.922l.869 1.411A1.75 1.75 0 0 1 18.368 9h-1.736a1.75 1.75 0 0 1-1.491-2.667l.869-1.411a1.75 1.75 0 0 1 2.98 0M5.5 16.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.w5f9tubjt {
  d: path("M6 12h3a3.5 3.5 0 0 1 3.5 3.5V18A3.5 3.5 0 0 1 9 21.5H6A3.5 3.5 0 0 1 2.5 18v-2.5A3.5 3.5 0 0 1 6 12m6.5 4.5c4 0 5-3 5-7.5");
}

</style>
