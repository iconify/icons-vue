<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o-x1nwbug"/><path class="pq9ok5deo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-area-duocolor-sharp" /></template>
<style>
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

.pq9ok5deo {
  d: path("M7 14v-2l3-3l3 3l6-6v10H7z");
}

</style>
