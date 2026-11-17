<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vry6c_9ri"/><path class="m75auvbbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:linear-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m75auvbbu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3.307 9.67l11.022 11.023M3.898 15.92l4.183 4.183M5.292 6a9 9 0 1 1 12.709 12.709Z");
}

.vry6c_9ri {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18.001 18.708L5.292 5.999a9.002 9.002 0 0 1 15.443 3.833a9 9 0 0 1-2.734 8.876");
}

</style>
