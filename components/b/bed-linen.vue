<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh0tggkew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bed-linen" /></template>
<style>
.fh0tggkew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5V20m0-7.5h16a2 2 0 0 1 2 2V20M3 16.5h18m-13.5-4V10A1.5 1.5 0 0 1 9 8.5h10.5A1.5 1.5 0 0 1 21 10v2.5m-10-4v4");
}

</style>
