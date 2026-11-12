<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gknnp24pm"/><path class="vj5vml4fs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:magnet-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gknnp24pm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 5a3 3 0 0 1 3-3h1a3 3 0 0 1 3 3v7a3 3 0 1 0 6 0V5a3 3 0 0 1 3-3h1a3 3 0 0 1 3 3v7c0 5.523-4.477 10-10 10S2 17.523 2 12Z");
}

.vj5vml4fs {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12V5a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2v7a4 4 0 1 0 8 0V5a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2v7a9 9 0 0 1-18 0m0-4h5m8 0h5");
}

</style>
