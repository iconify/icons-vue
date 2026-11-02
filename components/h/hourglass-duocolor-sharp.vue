<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yvebdkb2o"/><path class="wew2rgbhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hourglass-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wew2rgbhy {
  d: path("M7 3v4l5 5l-5 5v4M17 3v4l-5 5l5 5v4");
}

.yvebdkb2o {
  stroke-opacity: 0.4;
  d: path("M5 3h14M5 21h14");
}

</style>
