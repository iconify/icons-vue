<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ox81zdb2t"/><path class="csq-tc-oi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:headset-duocolor-sharp" /></template>
<style>
.csq-tc-oi {
  d: path("M5 10a7 7 0 0 1 14 0M3 10h5v7H3Zm13 0h5v7h-5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ox81zdb2t {
  stroke-opacity: 0.4;
  d: path("M21 15v6h-8");
}

</style>
