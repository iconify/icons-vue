<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ecu3uoboo"/><path class="syqkmbc0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:encore" /></template>
<style>
.ecu3uoboo {
  d: path("M4.5 18a8.75 8.75 0 1 1 15 0");
}

.syqkmbc0b {
  d: path("M5 15.5L4.5 18L2 17.5m6.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0V11m0 0l3 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
