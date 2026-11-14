<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="liciy5b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anomaly-score" /></template>
<style>
.liciy5b_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12H5l1.5-2L8 12l2-6.5l2 10l1.5-3.5h3.293m2.4 0H21.5M10 2.5h.01m7.99 12V18m0 3h.01");
}

</style>
