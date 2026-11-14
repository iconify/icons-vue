<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iti2o9b_o"/><path class="d8-p_9qwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-fearful" /></template>
<style>
.d8-p_9qwj {
  d: path("M10 15.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.iti2o9b_o {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Zm5-4.25l2.75-1.25m3.5 0l2.75 1.25M9 10.5h.01m5.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
