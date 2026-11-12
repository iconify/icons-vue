<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e0ql9gxfh"/><path class="m4ef2-b8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:latency-duocolor-sharp" /></template>
<style>
.e0ql9gxfh {
  stroke-opacity: 0.4;
  d: path("M8 14h2l1-3l2 6l1-3h2");
}

.m4ef2-b8e {
  d: path("M5 14a7 7 0 1 0 14 0a7 7 0 0 0-14 0M9 3h6m-3 0v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
