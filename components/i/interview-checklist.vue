<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y_rso8g0p"/><path class="punjz8myo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:interview-checklist" /></template>
<style>
.punjz8myo {
  d: path("m5.5 6.5l1 1l1.75-2m2.5 1h7.75M5.5 10l1 1l1.75-2m2.5 1h7.75m-13 3.5l1 1l1.75-2m2.5 1H16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_rso8g0p {
  d: path("M2.5 5A2.5 2.5 0 0 1 5 2.5h14A2.5 2.5 0 0 1 21.5 5v10a2.5 2.5 0 0 1-2.5 2.5h-8L7 21v-3.5H5A2.5 2.5 0 0 1 2.5 15Z");
}

</style>
