<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p63asp49u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fuel-consumption-ship" /></template>
<style>
.p63asp49u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.442 16.5H5L2.5 11h15m2 0h2l-.662 1.457M4.5 7H12v4H4.5Zm13 4H15V4h4.5v7m-1 3s2.75 3 2.75 5a2.75 2.75 0 0 1-5.5 0c0-2 2.75-5 2.75-5Z");
}

</style>
