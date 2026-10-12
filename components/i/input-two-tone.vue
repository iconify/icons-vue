<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sncq5wmtz"/><path class="k_0pz683h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:input-two-tone" /></template>
<style>
.k_0pz683h {
  d: path("M2 9C2 7.8954 2.8954 7 4 7L20 7C21.1046 7 22 7.8954 22 9L22 15C22 16.1046 21.1046 17 20 17L4 17C2.8954 17 2 16.1046 2 15L2 9ZM6 11L6 13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sncq5wmtz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 9C1 7.3431 2.3431 6 4 6L20 6C21.6569 6 23 7.3431 23 9L23 15C23 16.6569 21.6569 18 20 18L4 18C2.3431 18 1 16.6569 1 15L1 9Z");
  stroke: none;
}

</style>
