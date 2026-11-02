<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qah_-9ebo"/><path class="b1egz1dwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-lightning-duocolor-sharp" /></template>
<style>
.b1egz1dwh {
  d: path("M7 15a4 4 0 1 1 0-8c2-6 11-5 11 2a3 3 0 0 1 0 6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qah_-9ebo {
  stroke-opacity: 0.4;
  d: path("m13 15l-3 3h4l-3 3");
}

</style>
