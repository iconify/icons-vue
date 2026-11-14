<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k-go6bbvd"/><path class="w6zhzdb9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:claim-denied" /></template>
<style>
.k-go6bbvd {
  d: path("M13.1 19H3V2.5h13v9.6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w6zhzdb9h {
  d: path("M5.5 9.5c0-2.5 1.75-4 4-4s4 1.5 4 4Zm4 0V12c0 .75-.5 1.25-1.25 1.25S7 12.75 7 12m-1 4h6.1m2.9-1l6 6m0-6l-6 6");
}

</style>
