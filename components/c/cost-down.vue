<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hjjf4yaqz"/><path class="f28kt_bsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cost-down" /></template>
<style>
.f28kt_bsv {
  d: path("M3 8.5v3a5.5 2.75 0 0 0 11 0v-3M18.5 3v18m-3-3l3 3l3-3");
}

.hjjf4yaqz {
  d: path("M3 8.5a5.5 2.75 0 1 0 11 0a5.5 2.75 0 1 0-11 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
