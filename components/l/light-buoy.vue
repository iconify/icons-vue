<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kh2q6nzzd"/><path class="cmdma_o4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:light-buoy" /></template>
<style>
.cmdma_o4j {
  d: path("M10.5 7.5h3v3h-3ZM2.5 18h19M12 2.5v2.25M6.5 4.5L8 6m9.5-1.5L16 6");
}

.kh2q6nzzd {
  d: path("M7.5 15a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
