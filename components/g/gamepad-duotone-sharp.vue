<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q-vq7u6zb"/><path class="oklr0qbsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gamepad-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oklr0qbsy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5h18v14H3Zm4 7h6m-3-3v6m6-1h.01M18 10h.01");
}

.q-vq7u6zb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 5h18v14H3Z");
}

</style>
