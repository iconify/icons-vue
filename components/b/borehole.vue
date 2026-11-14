<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epufmkbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:borehole" /></template>
<style>
.epufmkbtj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3h8v3.5H4Zm2 3.5V20m4-13.5V20m-7.5 0h10m6-7.5c-1.25 1.75-3 3.75-3 6a3 3 0 0 0 6 0c0-2.25-1.75-4.25-3-6Z");
}

</style>
