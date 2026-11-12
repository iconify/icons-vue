<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yxe1yactt"/><path class="v2ocnvb1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:billboard-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v2ocnvb1m {
  d: path("M3 7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm4 8v6m10-6v6");
}

.yxe1yactt {
  stroke-opacity: 0.4;
  d: path("M7 7h10M7 11h6");
}

</style>
