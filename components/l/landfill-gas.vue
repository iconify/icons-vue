<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcpl-tban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:landfill-gas" /></template>
<style>
.gcpl-tban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5C4.5 16.75 8 15 12 15s7.5 1.75 9.5 5.5M15 15.25V9.5m-1.75 0h3.5m-3.5-2.75q-1-1.25 0-2.5t0-2.25m3.5 4.75q-1-1.25 0-2.5t0-2.25");
}

</style>
