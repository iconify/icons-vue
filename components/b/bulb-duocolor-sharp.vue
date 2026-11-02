<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fnzvalwps"/><path class="stbx04qiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bulb-duocolor-sharp" /></template>
<style>
.fnzvalwps {
  stroke-opacity: 0.4;
  d: path("M9 21h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.stbx04qiv {
  d: path("M15 15v3H9v-3c0-1.5-3-3.5-3-6a6 6 0 1 1 12 0c0 2.5-3 4.5-3 6");
}

</style>
