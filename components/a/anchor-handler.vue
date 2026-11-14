<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvorjobbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anchor-handler" /></template>
<style>
.bvorjobbl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3.5h6.5V9H5Zm10.748 10H5L2.5 9h19l-.68 1.224M18.5 13v8.5m-3-3a3 3 0 0 0 6 0m-4.5-2h3");
}

</style>
