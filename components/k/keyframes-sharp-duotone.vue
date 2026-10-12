<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="q5os0rb0d"/><path class="g_5ggwbjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:keyframes-sharp-duotone" /></template>
<style>
.g_5ggwbjn {
  stroke-opacity: 0.4;
  d: path("M14.8048 2.5482L21 12L14.8048 21.4518");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q5os0rb0d {
  fill: currentColor;
  d: path("M10.2477 2.4184L16.682 11.4184C16.8033 11.5881 16.8685 11.7914 16.8685 12C16.8685 12.2086 16.8033 12.4119 16.682 12.5816L10.2477 21.5816C10.06 21.8442 9.7571 22 9.4343 22C9.1115 22 8.8085 21.8442 8.6208 21.5816L2.1865 12.5816C2.0652 12.4119 2 12.2086 2 12C2 11.7914 2.0652 11.5881 2.1865 11.4184L8.6208 2.4184C8.8085 2.1558 9.1115 2 9.4343 2C9.7571 2 10.06 2.1558 10.2477 2.4184Z");
  stroke: none;
}

</style>
