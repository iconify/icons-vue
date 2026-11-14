<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg8h6hv_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish-measure" /></template>
<style>
.wg8h6hv_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5c2.5-3.75 8.5-4 11.5-1l4-2.5v7l-4-2.5c-3 3-9 2.75-11.5-1ZM2.5 14h19v6h-19ZM6 14v2.5M9.5 14v3.5M13 14v2.5m3.5-2.5v3.5");
}

</style>
