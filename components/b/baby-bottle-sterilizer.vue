<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jq497dthp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-bottle-sterilizer" /></template>
<style>
.jq497dthp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7V5a2 2 0 0 1 4 0v2M5 7h8v2.5H5Zm.5 2.5V19A2.5 2.5 0 0 0 8 21.5h2a2.5 2.5 0 0 0 2.5-2.5V9.5m4 8.5c-1.5-2 1.5-4 0-6s1.5-4 0-6m3.75 12c-1.5-2 1.5-4 0-6s1.5-4 0-6");
}

</style>
