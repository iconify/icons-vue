<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p289dcz6o"/><path class="cls2bponp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:edit-duotone-thin" /></template>
<style>
.cls2bponp {
  d: path("M5 19v-4L16 4l4 4L9 19Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p289dcz6o {
  fill: currentColor;
  d: path("M5 19v-4L16 4l4 4L9 19Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
