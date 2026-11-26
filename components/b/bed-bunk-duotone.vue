<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="drm4d6zam"/><path class="ycb2hqx0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-bunk-duotone" /></template>
<style>
.drm4d6zam {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 10L9 10C9.5523 10 10 9.5523 10 9L10 7C10 5.3431 8.6569 4 7 4L3 4C2.4477 4 2 4.4477 2 5L2 9C2 9.5523 2.4477 10 3 10ZM6 18L9 18C9.5523 18 10 17.5523 10 17L10 15C10 13.3431 8.6569 12 7 12L3 12C2.4477 12 2 12.4477 2 13L2 17C2 17.5523 2.4477 18 3 18Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ycb2hqx0b {
  d: path("M3 3L3 5M3 5L3 7L3 9M3 9L3 13M3 9L9 9M3 13L3 15L3 17M3 17L3 21M3 17L9 17M9 9L16 9M16 9L21 9M16 9L16 13M21 9L21 5L21 3M21 9L21 13M9 17L16 17M16 17L21 17M16 17L16 13M16 17L16 20L16 21M21 17L21 13M21 17L21 21M16 13L21 13");
}

</style>
