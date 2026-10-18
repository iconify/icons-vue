<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e1472_dor"/><path class="s43srub4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-thumbnails-two-tone" /></template>
<style>
.e1472_dor {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5C2 3.3431 3.3431 2 5 2L19 2C20.6569 2 22 3.3431 22 5L22 15C22 16.6569 20.6569 18 19 18L5 18C3.3431 18 2 16.6569 2 15L2 5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s43srub4t {
  d: path("M3 5C3 3.8954 3.8954 3 5 3L19 3C20.1046 3 21 3.8954 21 5L21 15C21 16.1046 20.1046 17 19 17L5 17C3.8954 17 3 16.1046 3 15L3 5ZM3 21L6 21M10.5 21L13.5 21M18 21L21 21");
}

</style>
