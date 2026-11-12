<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z649-m4ax"/><path class="po9tgl0kv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-round-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.po9tgl0kv {
  d: path("M10 15H12C15.3137 15 18 12.3137 18 9C18 5.68629 15.3137 3 12 3H8C4.68629 3 2 5.68629 2 9C2 10.5367 2.57771 11.9385 3.52779 13");
}

.z649-m4ax {
  d: path("M14 9H12C8.68629 9 6 11.6863 6 15C6 18.3137 8.68629 21 12 21H16C19.3137 21 22 18.3137 22 15C22 13.4633 21.4223 12.0615 20.4722 11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
