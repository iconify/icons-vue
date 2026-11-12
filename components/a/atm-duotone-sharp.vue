<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m7yxkeb4r"/><path class="gdljz8e0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:atm-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gdljz8e0n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17V3h18v14M7 6h10M3 10h4m10 0h4M7 10h10v11H7zm3 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.m7yxkeb4r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 21V10a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1");
}

</style>
