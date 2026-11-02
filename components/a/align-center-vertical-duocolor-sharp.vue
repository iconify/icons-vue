<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ew0v-7bvs"/><path class="fuettpbem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-center-vertical-duocolor-sharp" /></template>
<style>
.ew0v-7bvs {
  stroke-opacity: 0.4;
  d: path("M3 12h18");
}

.fuettpbem {
  d: path("M4 4v16h6V4Zm10 2v12h6V6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
