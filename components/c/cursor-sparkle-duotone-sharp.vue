<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="djvl61ypx"/><path class="m1exftaey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-sparkle-duotone-sharp" /></template>
<style>
.djvl61ypx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 3c.002 2.005 1.995 3.998 4 4c-2.005.002-3.998 1.995-4 4c-.002-2.005-1.995-3.998-4-4c2.005-.002 3.998-1.995 4-4m5.316 8.051l9 3a1 1 0 0 1 0 1.898l-1.465.488l.856.856a1 1 0 0 1 0 1.414l-2 2a1 1 0 0 1-1.414 0l-.856-.856l-.488 1.465a1 1 0 0 1-1.898 0l-3-9a1.001 1.001 0 0 1 1.265-1.265");
}

.ft5dv1b6b {
  fill: none;
}

.m1exftaey {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 12l9 3l-3 1l2 2l-2 2l-2-2l-1 3zM7 3c0 2 2 4 4 4c-2 0-4 2-4 4c0-2-2-4-4-4c2 0 4-2 4-4");
}

</style>
