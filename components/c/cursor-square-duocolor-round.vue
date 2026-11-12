<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zgt00bc2e"/><path class="pt8s_kbvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-square-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pt8s_kbvf {
  d: path("M3 5a2 2 0 1 1 4 0a2 2 0 0 1-4 0");
}

.zgt00bc2e {
  stroke-opacity: 0.4;
  d: path("m10 10l11 4l-5 2l-2 5z");
}

</style>
