<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzh5ajr_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:container-ship-loading" /></template>
<style>
.uzh5ajr_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16h18l-2.5 4.5h-13Zm2-5h4v5H5Zm5 0h4v5h-4Zm7-7.5V9m-2.5-2.5L17 9l2.5-2.5");
}

</style>
