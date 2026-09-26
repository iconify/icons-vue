<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="eo9ptsnwd"/><path class="ljh38-bcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x2-plus-sharp-two-tone" /></template>
<style>
.eo9ptsnwd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 1L20 1C20.5523 1 21 1.4477 21 2L21 11C21 11.5523 20.5523 12 20 12L12 12L12 20C12 20.5523 11.5523 21 11 21L2 21C1.4477 21 1 20.5523 1 20L1 2C1 1.4477 1.4477 1 2 1Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ljh38-bcz {
  d: path("M2 11L20 11L20 2L2 2L2 20L11 20L11 2M19 15L19 23M15 19L23 19");
}

</style>
