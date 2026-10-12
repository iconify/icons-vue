<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sncq5wmtz"/><path class="qozjpwdsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:input-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qozjpwdsd {
  d: path("M6 11L6 13");
}

.sncq5wmtz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 9C1 7.3431 2.3431 6 4 6L20 6C21.6569 6 23 7.3431 23 9L23 15C23 16.6569 21.6569 18 20 18L4 18C2.3431 18 1 16.6569 1 15L1 9Z");
  stroke: none;
}

</style>
