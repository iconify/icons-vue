<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dk9g05b2s"/><path class="p7owabb_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-sparkle-duotone-sharp" /></template>
<style>
.dk9g05b2s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 3c.002 1.005 1.995 2.998 3 3c-1.005.002-2.998 1.995-3 3c-.002-1.005-1.995-2.998-3-3c1.005-.002 2.998-1.995 3-3m.293 17.707l-3-3a1 1 0 0 1 0-1.414l12-12a1 1 0 0 1 1.414 0l5 5a1 1 0 0 1 0 1.414l-10 10A1 1 0 0 1 11 21H7a1 1 0 0 1-.707-.293");
}

.ft5dv1b6b {
  fill: none;
}

.p7owabb_k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 16l6-6l-5-5l-6 6m0 0l-6 6l3 3h4l4-4m-4 4h10m-11-9l5 5M6 3c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

</style>
