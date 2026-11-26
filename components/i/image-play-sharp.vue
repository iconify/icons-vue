<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m7fw3ko_y"/><path clip-rule="evenodd" class="vj2xmxbtx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-play-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m7fw3ko_y {
  d: path("M12 3L3 3L3 21L21 21L21 12M3 18L9 12L13 16L17 13L21 17M15 3.0011L20.9996 6L15 8.9989Z");
}

.vj2xmxbtx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 7.5C9.5 8.3284 8.8284 9 8 9C7.1716 9 6.5 8.3284 6.5 7.5C6.5 6.6716 7.1716 6 8 6C8.8284 6 9.5 6.6716 9.5 7.5Z");
  stroke: none;
}

</style>
