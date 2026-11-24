<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxa2dmz6j"/><path class="sniojv7el"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-close-corner-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sniojv7el {
  d: path("M11 21H4V9h16v2M8 9V7a4 4 0 1 1 8 0v2");
}

.vxa2dmz6j {
  stroke-opacity: 0.4;
  d: path("m16 16l4 4m0-4l-4 4");
}

</style>
