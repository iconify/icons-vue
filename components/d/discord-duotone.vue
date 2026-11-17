<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rna444b7o"/><path class="jlxvahb-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:discord-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jlxvahb-b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-2-6h2.03L15 4c1.5.16 3.04.49 4.43 1.5c1.57 5.67 1.67 9.83 1.17 11.45C20 18.33 18.86 20 17.33 20c-.5 0-2-2-2-3c-1.83.6-4.83.6-6.66 0c0 1-1.5 3-2 3C5.14 20 4 18.33 3.4 16.95C2.9 15.33 3 11.17 4.57 5.5C5.96 4.49 7.5 4.16 9 4l.97 2Z");
}

.rna444b7o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.97 6h4.06L15 4c1.598.171 3.109.541 4.43 1.5c1.57 5.67 1.67 9.83 1.17 11.45c-.56 1.287-1.683 3.048-3.27 3.05c-.5 0-2-2-2-3c-1.83.6-4.83.6-6.66 0c0 1-1.5 3-2 3c-1.587-.002-2.71-1.763-3.27-3.05c-.5-1.62-.4-5.78 1.17-11.45C5.891 4.541 7.402 4.171 9 4Z");
}

</style>
