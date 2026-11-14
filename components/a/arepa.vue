<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb-vjxb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arepa" /></template>
<style>
.cb-vjxb8d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12.5L20.25 7l-1-3.25l-16.5 5.5ZM2.5 16h19v4.5h-19Zm4 0c0-1.5 1.75-2.25 3.5-1.75q3-1.5 6 0c1.75-.75 3.5 0 3.5 1.75");
}

</style>
