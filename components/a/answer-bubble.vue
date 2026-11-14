<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mtov54nrz"/><path class="e54k3pb8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:answer-bubble" /></template>
<style>
.e54k3pb8t {
  d: path("M10.5 13.5v-1.75Q9 10.625 9 8.75a3 3 0 0 1 6 0q0 1.875-1.5 3v1.75Z");
}

.mtov54nrz {
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3h13A2.5 2.5 0 0 1 21 5.5V14a2.5 2.5 0 0 1-2.5 2.5H11l-4 4v-4H5.5A2.5 2.5 0 0 1 3 14Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
