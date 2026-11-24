<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nx4e6--5o"/><path class="z3ee-ypiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-edit-corner-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nx4e6--5o {
  stroke-opacity: 0.4;
  d: path("M14 21v-3l4-4l3 3l-4 4Z");
}

.z3ee-ypiu {
  d: path("M10 19H3V5h18v6M3 5l6 6h6l6-6");
}

</style>
