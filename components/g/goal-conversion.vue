<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsv_dmb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:goal-conversion" /></template>
<style>
.qsv_dmb9g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4c2.5-1.25 4.5 1.25 7 0s4.5 1.25 7 0v8.5c-2.5 1.25-4.5-1.25-7 0s-4.5-1.25-7 0M5 3v18.5m9.5-3.5l2.5 2.5l4.5-5");
}

</style>
