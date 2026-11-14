<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="asf-0gpsd"/><path class="tgfgyvzbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:four-day-week" /></template>
<style>
.asf-0gpsd {
  d: path("M3.5 4.5h17v17h-17Zm4.5-2v4m8-4v4m-12.5 3h17");
}

.tgfgyvzbz {
  d: path("M13.75 18.5v-6.25l-5 4h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
