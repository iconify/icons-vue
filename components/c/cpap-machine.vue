<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mfgo3ib6i"/><path class="oh7e5nh6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cpap-machine" /></template>
<style>
.mfgo3ib6i {
  d: path("M2.5 12h10v9.5h-10Zm10 4.5c4 0 5-3 5-7.5m0-6.5l4 6.5h-8Z");
}

.oh7e5nh6u {
  d: path("M5.5 16.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
