<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv9a2_xip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loan-valuation" /></template>
<style>
.bv9a2_xip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 10.5V7a3.5 3.5 0 0 1 7 0v3.5m-10 0h13v11h-13Zm14-1H21V15l-2.25 2.25L16.5 15Zm-4.25-4.25L16.5 9.5m2.25 2.5h.01M9 16h.01");
}

</style>
