<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="now253bdc"/><path class="sybrgdcsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-center-horizontal-duocolor-round" /></template>
<style>
.now253bdc {
  stroke-opacity: 0.4;
  d: path("M12 3v18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sybrgdcsx {
  d: path("M4 7a3 3 0 0 1 3-3h10a3 3 0 0 1 0 6H7a3 3 0 0 1-3-3m2 10a3 3 0 0 1 3-3h6a3 3 0 0 1 0 6H9a3 3 0 0 1-3-3");
}

</style>
