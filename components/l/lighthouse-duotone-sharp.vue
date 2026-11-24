<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t-h33qb0e"/><path class="ae3s899qw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lighthouse-duotone-sharp" /></template>
<style>
.ae3s899qw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12h6l3 9H6zm-2 0h10m-8 0V8H8l4-4l4 4h-1v4M3 21h18M7 18l9-3M3 9h2m14 0h2");
}

.ft5dv1b6b {
  fill: none;
}

.t-h33qb0e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 12V8H8l4-4l4 4h-1v4l3 9H6Z");
}

</style>
