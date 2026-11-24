<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mhf1aq5wk"/><path class="bemq4ubbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-heart-corner-duotone-round" /></template>
<style>
.bemq4ubbo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 17c-1.28 0-2.36.36-3 1l-1 1c-.738.738-2-.524-2-2V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v2m-4 7c-1-2-4-2-4 0s4 4 4 4s4-2 4-4s-3-2-4 0");
}

.ft5dv1b6b {
  fill: none;
}

.mhf1aq5wk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 13v4c-1.041 0-2.236.237-3 1l-1 1c-.738.738-2-.524-2-2V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v2h-8a4 4 0 0 0-4 4m8 3c1-2 4-2 4 0s-4 4-4 4s-4-2-4-4s3-2 4 0");
}

</style>
