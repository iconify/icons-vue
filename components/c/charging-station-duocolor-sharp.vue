<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zds7z8bri"/><path class="tl2f66b6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:charging-station-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tl2f66b6s {
  d: path("M3 3h10v18H3Zm10 9h4v5h4V7l-3-3");
}

.zds7z8bri {
  stroke-opacity: 0.4;
  d: path("m9 8l-3 4h4l-3 4");
}

</style>
