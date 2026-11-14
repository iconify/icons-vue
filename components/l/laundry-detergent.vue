<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rawxpbouk"/><path class="yis-7xbwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:laundry-detergent" /></template>
<style>
.rawxpbouk {
  d: path("M7 3h6v4H7ZM4 21V10a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v11ZM16 9h2a2.5 2.5 0 0 1 2.5 2.5v2A2.5 2.5 0 0 1 18 16h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yis-7xbwx {
  d: path("M10 11s-2.5 3-2.5 4.5a2.5 2.5 0 0 0 5 0C12.5 14 10 11 10 11Z");
}

</style>
