<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="waoze2boy"/><path class="e-9ewwb1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clapperboard-two-tone" /></template>
<style>
.e-9ewwb1s {
  d: path("M6 3H18C19.6569 3 21 4.3431 21 6V18C21 19.6569 19.6569 21 18 21H6C4.3431 21 3 19.6569 3 18V6C3 4.3431 4.3431 3 6 3ZM3 8H21M6.5 8L8.5 3M11 8L13 3M15.5 8L17.5 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.waoze2boy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 8L22 18C22 20.2092 20.2092 22 18 22L6 22C3.7908 22 2 20.2092 2 18L2 8Z");
  stroke: none;
}

</style>
