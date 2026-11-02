<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tlhce0b5x"/><path class="ntyt7mipc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:certificate-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ntyt7mipc {
  d: path("M9 17H7a4 4 0 0 1-4-4V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v10M7 7h10M7 11h2");
}

.tlhce0b5x {
  stroke-opacity: 0.4;
  d: path("M13 15a2.828 2.828 0 1 1 4-4a2.828 2.828 0 0 1-4 4m0 0v6l2-2l2 2v-6");
}

</style>
