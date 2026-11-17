<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="teyx6jb4p"/><path class="bhmicaciu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clapperboard-duotone-sharp" /></template>
<style>
.bhmicaciu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9h18v12H3Zm0-3l16-3l.563 3l-16 3zm5.333-1l.563 3m4.77-4l.563 3M10 12l5 3l-5 3z");
}

.ft5dv1b6b {
  fill: none;
}

.teyx6jb4p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m3 6l16-3l.563 3l-16 3Zm0 3h18v12H3Z");
}

</style>
