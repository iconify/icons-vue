<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="trazp4bfb"/><path class="sqi04ibqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:incognito-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.sqi04ibqn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m6 10l1-3c.597-1.792 2.208-3 4-3h2c1.792 0 3.403 1.208 4 3l1 3M3 10h18M4 17a3 3 0 1 0 6 0a3 3 0 0 0-6 0m10 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-4 0a2 2 0 1 1 4 0");
}

.trazp4bfb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m6 10l1-3c.577-1.728 2.149-2.999 4-3h2c1.851.001 3.423 1.272 4 3l1 3Z");
}

</style>
