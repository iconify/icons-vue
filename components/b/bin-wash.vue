<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agsgnubov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bin-wash" /></template>
<style>
.agsgnubov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8h12m-7.5-2.75h3M10.5 8l1 11.5A1.5 1.5 0 0 0 13 21h4a1.5 1.5 0 0 0 1.5-1.5l1-11.5m-15-4.5S2.75 5.75 2.75 7a1.75 1.75 0 0 0 3.5 0c0-1.25-1.75-3.5-1.75-3.5Zm2 8S4.75 13.75 4.75 15a1.75 1.75 0 0 0 3.5 0c0-1.25-1.75-3.5-1.75-3.5Z");
}

</style>
