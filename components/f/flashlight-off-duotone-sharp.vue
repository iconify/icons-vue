<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qe-6o75mp"/><path class="ixpqzkewc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flashlight-off-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ixpqzkewc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 6l6 6l-4 4h-3l-5 5l-3-3l5-5v-3zM9 9l6 6");
}

.qe-6o75mp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18.707 11.293a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 14 17h-2.586l-4.707 4.707a1 1 0 0 1-1.414 0l-3-3a1 1 0 0 1 0-1.414L7 12.586V10c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0Z");
}

</style>
