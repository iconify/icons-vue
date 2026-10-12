<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad5epwbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hostel-sharp" /></template>
<style>
.ad5epwbmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 3.25v18m15.5-18v18M4.25 10.5h15.5M4.25 18h15.5m-3-7.5V18m0-3.75h3M7.25 5.5h4.5V8h-4.5zm0 7.5h4.5v2.5h-4.5z");
}

</style>
