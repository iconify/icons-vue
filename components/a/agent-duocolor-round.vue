<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pu-76gbng"/><path class="hdi6-gpca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:agent-duocolor-round" /></template>
<style>
.hdi6-gpca {
  d: path("M5 13a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4Zm7-4V5m-1-1a1 1 0 1 0 2 0a1 1 0 0 0-2 0M5 15H3m16 0h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pu-76gbng {
  stroke-opacity: 0.4;
  d: path("M12 12c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

</style>
