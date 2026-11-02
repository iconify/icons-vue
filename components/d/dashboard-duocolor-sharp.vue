<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w3v_8-sey"/><path class="p6ibbnhnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dashboard-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p6ibbnhnw {
  d: path("M4 4h6v8H4Zm0 12h6v4H4Zm10-4h6v8h-6Z");
}

.w3v_8-sey {
  stroke-opacity: 0.4;
  d: path("M14 4h6v4h-6Z");
}

</style>
