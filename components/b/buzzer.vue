<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e8mvxtb2l"/><path class="ynbz27bzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:buzzer" /></template>
<style>
.e8mvxtb2l {
  d: path("M3 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ynbz27bzu {
  d: path("M6 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm10.5-5.25a9.25 9.25 0 0 1 0 10.5m3.25-11.5a12.5 12.5 0 0 1 0 12.5");
}

</style>
