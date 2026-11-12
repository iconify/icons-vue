<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fhtkvnjef"/><path class="wy01nzbdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:border-inner-duocolor-round" /></template>
<style>
.fhtkvnjef {
  stroke-opacity: 0.4;
  d: path("M6 12h12m-6-6v12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wy01nzbdr {
  d: path("M3 3h.01M9 3h.01M15 3h.01M21 3h-.01M21 9h-.01m.01 6h-.01m.01 6h-.01M15 21h.01M9 21h.01M3 21h.01M3 15h.01M3 9h.01");
}

</style>
