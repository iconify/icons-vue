<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7d9hjbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-icicle" /></template>
<style>
.l7d9hjbzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19V7h-19Zm0 7h8.25V14H2.5Zm10.75 0h8.25V14h-8.25Zm-10.75 7h2.75v5H2.5Zm5.5 0h2.75v5H8Zm5.25 0H16v5h-2.75Zm5.5 0h2.75v5h-2.75Z");
}

</style>
