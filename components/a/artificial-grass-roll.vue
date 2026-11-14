<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="giroj_n6k"/><path class="har_uhbbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:artificial-grass-roll" /></template>
<style>
.giroj_n6k {
  d: path("M2.5 11.75a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0m5.5 5.5h13.5");
}

.har_uhbbo {
  d: path("M8 9.25a2.5 2.5 0 1 1-2.5 2.5m9.5 5.5L16.5 13l1.5 4.25L19.5 13l1.5 4.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
