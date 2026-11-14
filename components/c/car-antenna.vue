<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fi74932-c"/><path class="g7qj0br1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-antenna" /></template>
<style>
.fi74932-c {
  d: path("M5 19H3v-4l4-1l2.5-3.5H15l3 3.5l3 1v4h-2M9 19h6");
}

.g7qj0br1v {
  d: path("M5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-4-8.5L9 5.25M7.625 7.632a2.75 2.75 0 0 1 0-4.764");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
