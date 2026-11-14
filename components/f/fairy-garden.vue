<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="axbpdz1hl"/><path class="e86pwt6me"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fairy-garden" /></template>
<style>
.axbpdz1hl {
  d: path("M3.5 16h17L19 21.5H5Zm.25 0v-4.25l4-4l4 4V16");
}

.e86pwt6me {
  d: path("M6.5 16v-2.25a1.25 1.25 0 0 1 2.5 0V16m5.5-3.5a3 3 0 0 1 6 0Zm3 0V16M18 2.75q0 2 2 2q-2 0-2 2q0-2-2-2q2 0 2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
