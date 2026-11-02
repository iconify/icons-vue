<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hek983yzr"/><path class="ymy21s4to"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eyedropper-duocolor-sharp" /></template>
<style>
.hek983yzr {
  stroke-opacity: 0.4;
  d: path("m14 13l1 1l4-4a3.536 3.536 0 0 0-5-5l-4 4l1 1");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ymy21s4to {
  d: path("m14 13l-5 5l-5 2l2-5l5-5M9 8l7 7");
}

</style>
