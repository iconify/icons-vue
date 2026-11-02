<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iin6arb5t"/><path class="ixfd0uity"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-conversation-duocolor-round" /></template>
<style>
.iin6arb5t {
  stroke-opacity: 0.4;
  d: path("M19 9a2 2 0 0 1 2 2v6c0 1.476-1.262 2.738-2 2l-1-1c-.64-.64-1.72-1-3-1H9");
}

.ixfd0uity {
  d: path("M3 10V7a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4H9c-1.28 0-2.36.36-3 1l-1 1c-.738.738-2-.524-2-2z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
