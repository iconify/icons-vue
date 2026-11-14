<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8_07accx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boat-party" /></template>
<style>
.e8_07accx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14h18l-2.75 3.5H5.75Zm3-4h6v4H6Zm9 4V3.5m0 0L20.5 14m-17 6.5q2.25-1.25 4.5 0t4.5 0t4.5 0t3.5.25");
}

</style>
