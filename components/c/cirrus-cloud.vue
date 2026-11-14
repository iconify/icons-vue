<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8-o1dbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cirrus-cloud" /></template>
<style>
.w8-o1dbin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8q6.75-3.75 18-3M5 13.5c5-2.5 10-3 16.5-2.5m-19 8C7 16.5 12 16 18 16.5");
}

</style>
