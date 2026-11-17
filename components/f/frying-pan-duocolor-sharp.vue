<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rqyts8bos"/><path class="nedp8zb0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:frying-pan-duocolor-sharp" /></template>
<style>
.nedp8zb0g {
  d: path("M3 11h12v5H3z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rqyts8bos {
  stroke-opacity: 0.4;
  d: path("m15 11l6-3");
}

</style>
