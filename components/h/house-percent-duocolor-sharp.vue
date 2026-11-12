<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y2esomwaf"/><path class="z_356sbxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-percent-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y2esomwaf {
  stroke-opacity: 0.4;
  d: path("m14 12l-4 4m0-4h.01M14 16h.01");
}

.z_356sbxy {
  d: path("m16 7l4 4v10H4V11l8-8z");
}

</style>
