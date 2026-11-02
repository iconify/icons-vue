<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z7ivyjbuf"/><path class="cw_0qobox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-coins-duocolor" /></template>
<style>
.cw_0qobox {
  d: path("m4 16l3-3c.6-.6 1.2-1 2-1h3a2 2 0 1 1 0 4h-2m4-2l3-3a2.121 2.121 0 1 1 3 3l-5 5c-.64.64-1.36 1-2 1H8m-5-5l6 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z7ivyjbuf {
  stroke-opacity: 0.4;
  d: path("M7 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m7-1a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
