<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e-83y7b1x"/><path class="ux78ty71o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:inbox-duotone-round" /></template>
<style>
.e-83y7b1x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 12c1.317 0 2.748.335 3.707 1.293l1 1c.948.948 3.638.948 4.586 0l1-1C16.252 12.335 17.683 12 19 12h2a1 1 0 0 1 1 1v3a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5v-3a1 1 0 0 1 1-1Z");
}

.ft5dv1b6b {
  fill: none;
}

.ux78ty71o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v8a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm0 5h2c1.28 0 2.36.36 3 1l1 1c.64.64 1.72 1 3 1s2.36-.36 3-1l1-1c.64-.64 1.72-1 3-1h2");
}

</style>
