<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ueki5cbyx"/><path class="oi84idb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-thumbnails-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oi84idb2v {
  d: path("M3 21L6 21M10.5 21L13.5 21M18 21L21 21");
}

.ueki5cbyx {
  fill: currentColor;
  d: path("M2 5C2 3.3431 3.3431 2 5 2L19 2C20.6569 2 22 3.3431 22 5L22 15C22 16.6569 20.6569 18 19 18L5 18C3.3431 18 2 16.6569 2 15L2 5Z");
  stroke: none;
}

</style>
