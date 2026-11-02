<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o-x1nwbug"/><path class="eq8drccgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-gantt-duocolor-sharp" /></template>
<style>
.eq8drccgj {
  d: path("M7 8h6m-3 4h7m-3 4h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o-x1nwbug {
  stroke-opacity: 0.4;
  d: path("M3 4v16h18");
}

</style>
