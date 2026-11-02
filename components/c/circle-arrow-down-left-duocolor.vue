<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iou_y8bpw"/><path class="q_a5zcbnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-arrow-down-left-duocolor" /></template>
<style>
.iou_y8bpw {
  stroke-opacity: 0.4;
  d: path("M13 15H9v-4m0 4l6-6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q_a5zcbnk {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0");
}

</style>
