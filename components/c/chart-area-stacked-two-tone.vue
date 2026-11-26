<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wd6371bec"/><path class="m3uk6zbfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-area-stacked-two-tone" /></template>
<style>
.m3uk6zbfe {
  d: path("M3 18.8L10.7143 12.2L14.5714 15.5L21 10V20C21 20.5523 20.5523 21 20 21H4C3.4477 21 3 20.5523 3 20V18.8ZM3 12L10.7143 5.25L14.5714 8.625L21 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wd6371bec {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 22L4 22C2.8954 22 2 21.1046 2 20L2 18.8C2 18.5078 2.1278 18.2301 2.3499 18.0401L10.0642 11.4401C10.2454 11.2852 10.4759 11.2 10.7143 11.2C10.9527 11.2 11.1833 11.2852 11.3644 11.4402L14.5714 14.184L20.3499 9.2401C20.5311 9.0852 20.7616 9 21 9C21.5523 9 22 9.4477 22 10L22 20C22 21.1046 21.1046 22 20 22Z");
  stroke: none;
}

</style>
