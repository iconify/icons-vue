<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p289dcz6o"/><path class="cls2bponp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:edit-duotone-bold" /></template>
<style>
.cls2bponp {
  d: path("M5 19v-4L16 4l4 4L9 19Z");
}

.p289dcz6o {
  fill: currentColor;
  d: path("M5 19v-4L16 4l4 4L9 19Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
