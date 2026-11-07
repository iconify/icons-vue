<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i0807y2wg"/><path class="nvvco_bxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-off-duocolor" /></template>
<style>
.i0807y2wg {
  stroke-opacity: 0.4;
  d: path("m16 10l4-4M2 2l20 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nvvco_bxg {
  d: path("M12 19H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2m6 0h8a2 2 0 0 1 2 2v8m-2 4h-7");
}

</style>
