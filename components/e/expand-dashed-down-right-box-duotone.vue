<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ps2rzbltq"/><path class="d8ry_7lch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-down-right-box-duotone" /></template>
<style>
.d8ry_7lch {
  stroke-opacity: 0.4;
  d: path("M21 16L21 18M18 21L16 21M13 18L13 16M18 13L16 13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ps2rzbltq {
  d: path("M11 6L21 6M18 9L21 6L18 3M6 11L6 21M3 18L6 21L9 18");
}

</style>
