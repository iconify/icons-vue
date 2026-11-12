<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k_a5rsc0b"/><path class="xu7la8b8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:function-arrow-right-duocolor" /></template>
<style>
.k_a5rsc0b {
  stroke-opacity: 0.4;
  d: path("M13 14h8m-3-3l3 3l-3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xu7la8b8s {
  d: path("M13 4c-3 0-3 0-4 4l-2 8c-1 4-1 4-4 4m2-10h7");
}

</style>
