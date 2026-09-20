<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zhm5t29_o"/><path class="qfm0f643r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:experiment-duotone-bold" /></template>
<style>
.qfm0f643r {
  d: path("M9 3v7l-5 5v4h16v-4l-5 -5V3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zhm5t29_o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 3v7l-5 5v4h16v-4l-5 -5V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
