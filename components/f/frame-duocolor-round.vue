<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sk6uw-bym"/><path class="i8ptlcpac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:frame-duocolor-round" /></template>
<style>
.i8ptlcpac {
  d: path("M7 7h10v10H7Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sk6uw-bym {
  stroke-opacity: 0.4;
  d: path("M3 7h4m10 0h4M3 17h4m10 0h4M7 3v4m10-4v4M7 17v4m10-4v4");
}

</style>
