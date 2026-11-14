<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7-u9dbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:business-marine-cargo" /></template>
<style>
.t7-u9dbpu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19L19 16.5H5ZM6 8h5.5v4H6Zm5.5 0H17v4h-5.5ZM8.75 4h5.5v4h-5.5ZM3 20q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
