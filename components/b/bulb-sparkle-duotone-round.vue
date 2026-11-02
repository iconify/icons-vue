<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s50jjhbny"/><path class="t8b2b0ped"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bulb-sparkle-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.s50jjhbny {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 16a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2v-1c0-1.5-3-3.5-3-6a6 6 0 1 1 12 0c0 2.5-3 4.5-3 6Z");
}

.t8b2b0ped {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 15v1a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2v-1c0-1.5-3-3.5-3-6a6 6 0 1 1 12 0c0 2.5-3 4.5-3 6m-6 6h6M12 6c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

</style>
