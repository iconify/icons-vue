<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p37-48m8n"/><path class="evltpmrki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cog-railway-duocolor" /></template>
<style>
.evltpmrki {
  d: path("M6 19V9a2 2 0 0 1 2-2h3V6a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2v7zm0-7h5V9h7m-7-2v2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p37-48m8n {
  stroke-opacity: 0.4;
  d: path("m4 20l16-8M6 19l1 2m3-4l1 2m3-4l1 2m3-4l1 2");
}

</style>
