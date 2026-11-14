<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nua9-2d2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electric-current-flow" /></template>
<style>
.nua9-2d2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.991 15.245L16.5 9.75h-6.25L11 2.5l-8 10h6.25l-.75 7l3.237-3.946M14.5 18h7m-3-3l3 3l-3 3");
}

</style>
