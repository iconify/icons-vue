<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i0ysfwbvp"/><path class="bad1egbwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donate-coat" /></template>
<style>
.bad1egbwz {
  d: path("m18 21.5l-3.25-3.25a2 2 0 0 1 3.25-2a2 2 0 0 1 3.25 2Z");
}

.i0ysfwbvp {
  d: path("M13.034 20.5H5.5v-6l-3-.5L5 4.25L8.5 3l3 2.5l3-2.5L18 4.25l2.229 8.692M11.5 5.5v15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
