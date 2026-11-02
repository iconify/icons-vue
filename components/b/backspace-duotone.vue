<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xesai7u0b"/><path class="ls_x5gbcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backspace-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ls_x5gbcj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 6h4a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H9l-5-5a1.414 1.414 0 0 1 0-2l5-5zm-2 4l4 4m0-4l-4 4");
}

.xesai7u0b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 6h4a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H9l-5-5a1.415 1.415 0 0 1 0-2l5-5Z");
}

</style>
