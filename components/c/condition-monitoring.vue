<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="prbdkyb7v"/><path class="x99fvy-7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:condition-monitoring" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.prbdkyb7v {
  d: path("M7.375 4.5h5.25A4.375 4.375 0 0 1 17 8.875v4.25a4.375 4.375 0 0 1-4.375 4.375h-5.25A4.375 4.375 0 0 1 3 13.125v-4.25A4.375 4.375 0 0 1 7.375 4.5M5.5 17.5l-1 3h11l-1-3M17 11h4.5");
}

.x99fvy-7v {
  d: path("M5.5 11h2L9 8l2 6l1.5-3h2");
}

</style>
