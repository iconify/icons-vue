<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu17rlb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boatyard" /></template>
<style>
.gu17rlb4w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10h16.5L17 15.5H5.5A1.5 1.5 0 0 1 4 14Zm6.5 0V3.5l6 6.5m-9 5.5v5m7-5v5M3 20.5h18");
}

</style>
