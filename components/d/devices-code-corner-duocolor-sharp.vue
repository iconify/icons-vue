<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zxl6wqb0d"/><path class="qpy5vjbdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:devices-code-corner-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qpy5vjbdd {
  d: path("M15 3h6v10h-6Zm-4 1H3v12h7");
}

.zxl6wqb0d {
  stroke-opacity: 0.4;
  d: path("m15 17l-2 2l2 2m4-4l2 2l-2 2");
}

</style>
