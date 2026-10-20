<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ijrr61bnd"/><path class="s7n0apa8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x2-check-two-tone" /></template>
<style>
.ijrr61bnd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 1L17 1C19.2091 1 21 2.7909 21 5L21 9C21 10.6569 19.6569 12 18 12L12 12L12 18C12 19.6569 10.6569 21 9 21L5 21C2.7909 21 1 19.2091 1 17L1 5C1 2.7909 2.7909 1 5 1Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s7n0apa8v {
  d: path("M2 11L18 11C19.1046 11 20 10.1046 20 9L20 5C20 3.3431 18.6569 2 17 2L5 2C3.3431 2 2 3.3431 2 5L2 17C2 18.6569 3.3431 20 5 20L9 20C10.1046 20 11 19.1046 11 18L11 2M16 19.6L18.3333 22L22 16");
}

</style>
