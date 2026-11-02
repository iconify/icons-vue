<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bjp0usbso"/><path class="urp0a5bwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:biohazard-duocolor-sharp" /></template>
<style>
.bjp0usbso {
  stroke-opacity: 0.4;
  d: path("M10.428 5.693a6.5 6.5 0 0 1 3.144 0m4.676 8.099a6.5 6.5 0 0 1-1.572 2.723m-9.352 0a6.5 6.5 0 0 1-1.572-2.723");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.urp0a5bwc {
  d: path("M16.447 19.796A6 6 0 0 1 12 14a6 6 0 0 1-4.447 5.796m-4.528-7.842A6 6 0 0 1 10.268 11a6 6 0 0 1-2.796-6.75m9.056 0A6 6 0 0 1 13.732 11a6 6 0 0 1 7.243.954M10 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
