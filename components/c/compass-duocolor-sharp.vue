<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r0w_mnbgf"/><path class="q_a5zcbnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:compass-duocolor-sharp" /></template>
<style>
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

.r0w_mnbgf {
  stroke-opacity: 0.4;
  d: path("m12 7l2 5l-2 5l-2-5Z");
}

</style>
