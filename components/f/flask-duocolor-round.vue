<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tlzu35bzk"/><path class="t54msjkmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flask-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t54msjkmu {
  d: path("M10 3v6l-4 8c-.919 1.838.162 4 2 4h8c1.838 0 2.919-2.162 2-4l-4-8V3M8 3h8");
}

.tlzu35bzk {
  stroke-opacity: 0.4;
  d: path("M7 15h10");
}

</style>
