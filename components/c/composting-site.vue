<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3vsnibyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:composting-site" /></template>
<style>
.s3vsnibyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21c0-4 2-6.5 5-6.5c.5-3 2.5-4.5 5-4.5s4.5 2 4.5 4c2.5 0 4.5 2.5 4.5 7ZM7 18h3m3.5-.5h3m-4-7.5V5m0 2c0-2.5 2-4.5 5-4.5c0 2.5-2 4.5-5 4.5Z");
}

</style>
