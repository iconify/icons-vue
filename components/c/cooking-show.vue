<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dinns5-0u"/><path class="hy1de4b2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cooking-show" /></template>
<style>
.dinns5-0u {
  d: path("M6 8h12a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-6.5A3.5 3.5 0 0 1 6 8m2-5l4 5l4-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hy1de4b2q {
  d: path("M6 12h12M7.5 12v3.5a2 2 0 0 0 2 2h5a2 2 0 0 0 2-2V12");
}

</style>
