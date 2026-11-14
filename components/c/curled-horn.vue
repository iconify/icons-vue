<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmxtsi3cb"/><path class="yq8m0nbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:curled-horn" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qmxtsi3cb {
  d: path("M3 19C2.5 8 8 3 13.5 3c5 0 8 4 8 8.5c0 5-4.5 7.5-8 7.5c-2.5 0-4-2.5-4-5s1.5-4 3.75-4c1.75 0 3 1.25 2.5 2.75");
}

.yq8m0nbov {
  d: path("M6.25 19C5.75 11 9 5.75 13.5 5.75c3.5 0 5 2.75 5 5.75M3 19h3.25");
}

</style>
