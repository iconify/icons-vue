<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r812tbc0v"/><path class="en26wib3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-sparkle-duotone-round" /></template>
<style>
.en26wib3c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h5a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4H9c-1.28 0-2.36.36-3 1l-1 1c-.738.738-2-.524-2-2V7a4 4 0 0 1 4-4zm0 3c0 2 2 4 4 4c-2 0-4 2-4 4c0-2-2-4-4-4c2 0 4-2 4-4");
}

.ft5dv1b6b {
  fill: none;
}

.r812tbc0v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 3a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4H9c-1.041 0-2.236.237-3 1l-1 1c-.738.738-2-.524-2-2V7a4 4 0 0 1 4-4Z");
}

</style>
