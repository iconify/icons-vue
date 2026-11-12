<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f969racrb"/><path class="h6igbfesr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:magnet-duotone-sharp" /></template>
<style>
.f969racrb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 3a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v9a3 3 0 1 0 6 0V3a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v9c0 5.523-4.477 10-10 10S2 17.523 2 12Z");
}

.ft5dv1b6b {
  fill: none;
}

.h6igbfesr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12V3h5v9a4 4 0 1 0 8 0V3h5v9a9 9 0 0 1-18 0m0-4h5m8 0h5");
}

</style>
