<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iir8yebsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hot-plate" /></template>
<style>
.iir8yebsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5h19V21h-19ZM6 17.75h5M7 11.5Q5.5 9.25 7 7.25Q8.5 5 7 3m5 8.5q-1.5-2.25 0-4.25Q13.5 5 12 3m5 8.5q-1.5-2.25 0-4.25Q18.5 5 17 3");
}

</style>
