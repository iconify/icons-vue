<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgz75lb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:list-ordered" /></template>
<style>
.cgz75lb-n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 6.5h10m-10 8.25h10M4 5l1.5-1v5M4 13.25c0-1.05.7-1.75 1.5-1.75S7 12.1 7 13c0 1.5-3 2.5-3 4h3");
}

</style>
