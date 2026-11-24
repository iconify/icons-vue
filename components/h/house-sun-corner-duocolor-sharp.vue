<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zn1f4bb2f"/><path class="g5s6ahb7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-sun-corner-duocolor-sharp" /></template>
<style>
.g5s6ahb7t {
  d: path("M8 21H4V10l8-7l5.714 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zn1f4bb2f {
  stroke-opacity: 0.4;
  d: path("M15.5 16.5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m5 0h.5m-1.672 2.828l.354.354M16.5 20.5v.5m-2.828-1.672l-.354.354M12.5 16.5H12m1.672-2.828l-.354-.354M16.5 12.5V12m2.828 1.672l.354-.354");
}

</style>
