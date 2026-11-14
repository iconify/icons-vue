<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwf1ogbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-coverage" /></template>
<style>
.qwf1ogbvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13C2.5 8 7 5 12 5s9.5 3 9.5 8c-1.5-1-2.75-1-4.25 0c-1.5-1-3-1-5.25 0c-2.25-1-3.75-1-5.25 0c-1.5-1-2.75-1-4.25 0ZM12 3v2M2.5 18H7l2-3l2.5 6l2.5-5l1.5 2h6");
}

</style>
