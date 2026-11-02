<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tlhce0b5x"/><path class="zpj22hu2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:certificate-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tlhce0b5x {
  stroke-opacity: 0.4;
  d: path("M13 15a2.828 2.828 0 1 1 4-4a2.828 2.828 0 0 1-4 4m0 0v6l2-2l2 2v-6");
}

.zpj22hu2c {
  d: path("M9 17H3V3h18v14M7 7h10M7 11h2");
}

</style>
