<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pnc_lns1w"/><path class="sbr48yc6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-plus-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pnc_lns1w {
  stroke-opacity: 0.4;
  d: path("M15 6h6m-3-3v6");
}

.sbr48yc6l {
  d: path("M21 13v2a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h4M4 7l3 3c.64.64 1.72 1 3 1h3");
}

</style>
