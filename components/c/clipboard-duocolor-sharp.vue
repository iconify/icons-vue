<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hwr45wbpb"/><path class="ib9i7gbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-duocolor-sharp" /></template>
<style>
.hwr45wbpb {
  stroke-opacity: 0.4;
  d: path("M9 5V3h6v2M9 5v2h6V5");
}

.ib9i7gbfo {
  d: path("M9 5H5v16h14V5h-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
