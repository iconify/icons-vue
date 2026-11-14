<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwbs2db7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fencing-shoes" /></template>
<style>
.bwbs2db7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18V8c0-1 .75-1.5 1.75-1.5H7c1 0 1.75 2.25 4 2.75l6 1.25c3 .5 4.5 2.5 4.5 5V18Zm0-2.75h19m-9-5.5l1 2.75");
}

</style>
