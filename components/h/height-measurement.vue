<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eguc_q_sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:height-measurement" /></template>
<style>
.eguc_q_sw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h6v19H5ZM11 7H8m3 5H7m4 5H8m9-14v18M14.75 5.25L17 3l2.25 2.25m-4.5 13.5L17 21l2.25-2.25");
}

</style>
