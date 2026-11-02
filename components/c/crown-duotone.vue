<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="es6xs_gcj"/><path class="ndhtwub-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crown-duotone" /></template>
<style>
.es6xs_gcj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m16 10l5-4l-1.701 9.358A2 2 0 0 1 17.331 17H6.669a2 2 0 0 1-1.968-1.642L3 6l5 4l4-6Z");
}

.ft5dv1b6b {
  fill: none;
}

.ndhtwub-a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 4l4 6l5-4l-1.701 9.358A2 2 0 0 1 17.33 17H6.669a2 2 0 0 1-1.968-1.642L3 6l5 4zM5 21h14");
}

</style>
