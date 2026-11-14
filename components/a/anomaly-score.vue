<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py1xsuqve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anomaly-score" /></template>
<style>
.py1xsuqve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12H5l1.5-2L8 12l2-6.5l2 10l1.5-3.5h1.693m5.6 0h.707M10 2.5h.01m7.99 12V18m0 3h.01");
}

</style>
