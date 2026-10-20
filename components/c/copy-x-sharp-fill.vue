<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wuu1xwb6p"/><path clip-rule="evenodd" class="hzy0-i19j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-x-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hzy0-i19j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 7L22 7C22.5523 7 23 7.4477 23 8L23 22C23 22.5523 22.5523 23 22 23L8 23C7.4477 23 7 22.5523 7 22L7 8C7 7.4477 7.4477 7 8 7ZM16.4142 15L19 12.4142L17.5858 11L15 13.5858L12.4142 11L11 12.4142L13.5858 15L11 17.5858L12.4142 19L15 16.4142L17.5858 19L19 17.5858L16.4142 15Z");
  stroke: none;
}

.wuu1xwb6p {
  d: path("M16 5L16.0001 2L2 2L2 16.0001L5 16");
}

</style>
