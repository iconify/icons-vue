<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uzg4s8nlh"/><path class="alvvkqdcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-duotone" /></template>
<style>
.alvvkqdcf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 16l5-5a1.414 1.414 0 0 0 0-2l-4-4a1.414 1.414 0 0 0-2 0l-5 5m2 10h10M9 10l6 6m-6-6l-5 5a1.414 1.414 0 0 0 0 2l3 3h4l4-4");
}

.ft5dv1b6b {
  fill: none;
}

.uzg4s8nlh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 17a1.415 1.415 0 0 1 0-2L14 5a1.415 1.415 0 0 1 2 0l4 4a1.415 1.415 0 0 1 0 2l-9 9H7Z");
}

</style>
