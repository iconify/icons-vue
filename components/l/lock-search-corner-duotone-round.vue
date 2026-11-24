<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nppu5sxnl"/><path class="ri6fu062n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-search-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nppu5sxnl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 21a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4h7a4 4 0 0 0-4 4v8Z");
}

.ri6fu062n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 21H8a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4h8a4 4 0 0 1 3.464 2M8 9V7a4 4 0 1 1 8 0v2m4 11a2.828 2.828 0 1 1-4-4a2.828 2.828 0 0 1 4 4m0 0l2 2");
}

</style>
