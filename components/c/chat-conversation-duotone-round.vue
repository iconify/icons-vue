<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s5tyfnvkk"/><path class="agtdj4b1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-conversation-duotone-round" /></template>
<style>
.agtdj4b1h {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 10V7a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4H9c-1.28 0-2.36.36-3 1l-1 1c-.738.738-2-.524-2-2zm16-1a2 2 0 0 1 2 2v6c0 1.476-1.262 2.738-2 2l-1-1c-.64-.64-1.72-1-3-1H9");
}

.ft5dv1b6b {
  fill: none;
}

.s5tyfnvkk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 7a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v2a5 5 0 0 1-5 5H9c-.749 0-1.737.152-2.293.707l-1 1a1.71 1.71 0 0 1-1.498.485c-.461-.078-.866-.328-1.193-.655a3.4 3.4 0 0 1-.732-1.116A3.7 3.7 0 0 1 2 13Z");
}

</style>
