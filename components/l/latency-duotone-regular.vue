<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="unzah8ysn"/><path class="qfcrftzhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:latency-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qfcrftzhy {
  d: path("M4 3h16l-8 8 8 8H4l8 -8Z");
}

.unzah8ysn {
  fill: currentColor;
  d: path("M4 3h16l-8 8 8 8H4l8 -8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
