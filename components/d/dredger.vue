<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h20e3j12l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dredger" /></template>
<style>
.h20e3j12l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9h15l-2 4h-11ZM12 9l2-4m0 0l7 14M2.5 16.5q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
