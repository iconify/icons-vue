<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qgm4y23bk"/><path class="tw8j10bcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:layer-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qgm4y23bk {
  stroke-opacity: 0.4;
  d: path("m4 14l8 4l8-4");
}

.tw8j10bcb {
  d: path("m8 8l4-2l8 4l-8 4l-8-4z");
}

</style>
