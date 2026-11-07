<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="axcf-wb4p"/><path class="b-1gkojdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-off-duocolor-sharp" /></template>
<style>
.axcf-wb4p {
  stroke-opacity: 0.4;
  d: path("m2 2l20 20");
}

.b-1gkojdj {
  d: path("m18 19l-2 1a8.94 8.94 0 0 1-8 0l-5 1l1-5a8.94 8.94 0 0 1 0-8l1-2m5-3a9.22 9.22 0 0 1 11 11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
