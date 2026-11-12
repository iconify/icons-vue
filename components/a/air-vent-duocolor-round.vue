<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x-uhxaclo"/><path class="ndyherbvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:air-vent-duocolor-round" /></template>
<style>
.ndyherbvx {
  d: path("M3 7a4 4 0 0 1 4-4h2a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm3 0v10m4-10v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x-uhxaclo {
  stroke-opacity: 0.4;
  d: path("M17 7h4m-4 5h4m-4 5h4");
}

</style>
