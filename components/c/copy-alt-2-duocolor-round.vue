<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="owr9x_bqs"/><path class="psgwxtbcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-alt-2-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.owr9x_bqs {
  stroke-opacity: 0.4;
  d: path("M9 5a2 2 0 0 1 2-2h6a4 4 0 0 1 4 4v6a2 2 0 0 1-2 2");
}

.psgwxtbcu {
  d: path("M3 13a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z");
}

</style>
