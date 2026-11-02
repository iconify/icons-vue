<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rwvau1b_s"/><path class="dm9hnjnqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:agent-duotone-round" /></template>
<style>
.dm9hnjnqe {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 13a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4Zm7-4V5m-1-1a1 1 0 1 0 2 0a1 1 0 0 0-2 0M5 15H3m16 0h2m-9-3c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

.ft5dv1b6b {
  fill: none;
}

.rwvau1b_s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 5a1 1 0 1 1 0-2a1 1 0 0 1 0 2M9 9h6a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4");
}

</style>
