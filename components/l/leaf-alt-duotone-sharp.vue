<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x4yyzib4l"/><path class="g663zqz4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:leaf-alt-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g663zqz4y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 18c6.22 0 10.5-3.29 11-12V4h-4C7 4 4 8 4 13c0 1 0 3 2 5zm-4 3c.1-.7.4-1.8 1-3m0 0c1.5-3 3-6 6-7");
}

.x4yyzib4l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 6c-.41 7.085-3.394 11.996-11 12H6c-2-2-2-4-2-5c0-5 3-9 12-9h4Z");
}

</style>
