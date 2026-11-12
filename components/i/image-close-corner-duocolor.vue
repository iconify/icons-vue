<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxa2dmz6j"/><path class="el2-dfzza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-close-corner-duocolor" /></template>
<style>
.el2-dfzza {
  d: path("M11 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v6M3 17l5-5a1.414 1.414 0 0 1 2 0l1 1m3-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vxa2dmz6j {
  stroke-opacity: 0.4;
  d: path("m16 16l4 4m0-4l-4 4");
}

</style>
