<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="e-hq_cb3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:insurance-card" /></template>
<style>
.e-hq_cb3c {
  d: path("M5.5 12c0-2.5 1.75-4 4-4s4 1.5 4 4Zm4 0v2.5c0 .75-.5 1.25-1.25 1.25S7 15.25 7 14.5m9-4.5h2.5M16 13.5h2.5");
}

.hn7tnnbwb {
  d: path("M2.5 5h19v14h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
