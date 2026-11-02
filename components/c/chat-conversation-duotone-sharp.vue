<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ddg2szbey"/><path class="g8hgg_1vh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-conversation-duotone-sharp" /></template>
<style>
.ddg2szbey {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 2a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H7.414l-3.707 3.707A1 1 0 0 1 2 17V3a1 1 0 0 1 1-1Z");
}

.ft5dv1b6b {
  fill: none;
}

.g8hgg_1vh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h12v10H7l-4 4zm16 6h2v12l-4-4H9");
}

</style>
