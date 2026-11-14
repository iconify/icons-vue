<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmw_if7nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:extendable-table" /></template>
<style>
.lmw_if7nh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.5h19v3h-19Zm6.5 0v3m6-3v3m-10 0v10m14-10v10m-10.5-5h7M10 12l-1.5 1.5L10 15m4-3l1.5 1.5L14 15");
}

</style>
