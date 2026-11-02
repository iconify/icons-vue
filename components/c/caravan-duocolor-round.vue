<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t94gj4ktc"/><path class="dw1-2hblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caravan-duocolor-round" /></template>
<style>
.dw1-2hblb {
  d: path("M8 18H5a2 2 0 0 1-2-2V9a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v7a2 2 0 0 1-2 2h-3m-5-8a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t94gj4ktc {
  stroke-opacity: 0.4;
  d: path("M8 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m9-3h4");
}

</style>
