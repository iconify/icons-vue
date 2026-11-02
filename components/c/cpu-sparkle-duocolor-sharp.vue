<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pie5oxg6b"/><path class="wcypcrblw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cpu-sparkle-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pie5oxg6b {
  stroke-opacity: 0.4;
  d: path("M12 8c0 2 2 4 4 4c-2 0-4 2-4 4c0-2-2-4-4-4c2 0 4-2 4-4");
}

.wcypcrblw {
  d: path("M5 5h14v14H5Zm3-2v2m0 14v2M3 8h2m14 0h2m-9-5v2m0 14v2m-9-9h2m14 0h2m-5-9v2m0 14v2M3 16h2m14 0h2");
}

</style>
