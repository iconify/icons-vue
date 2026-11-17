<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="od4oxubpg"/><path class="cxxf0rb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:blinds-duocolor-round" /></template>
<style>
.cxxf0rb9f {
  d: path("M3 3h18M5 3v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V3M5 7h14M5 11h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.od4oxubpg {
  stroke-opacity: 0.4;
  d: path("M12 15v2m-2 2a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
