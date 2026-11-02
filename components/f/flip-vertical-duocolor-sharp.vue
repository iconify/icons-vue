<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zev_s31rm"/><path class="wr7858syx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wr7858syx {
  d: path("m7 3l5 5l5-5zm-2 9h2m4 0h2m4 0h2");
}

.zev_s31rm {
  stroke-opacity: 0.4;
  d: path("m7 21l5-5l5 5z");
}

</style>
