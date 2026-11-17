<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qdvoo5fxg"/><path class="bvq-c3hfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gas-cylinder-duotone-round" /></template>
<style>
.bvq-c3hfd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7h4a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4zM8 19v2h8v-2M4 13h16M8 7V5a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2");
}

.ft5dv1b6b {
  fill: none;
}

.qdvoo5fxg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 3h4a2 2 0 1 1 0 4h2a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4v2H8v-2a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4h2a2 2 0 1 1 0-4");
}

</style>
