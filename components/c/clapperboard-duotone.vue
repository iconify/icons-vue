<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="su516sdxu"/><path class="d3e0_z3po"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clapperboard-duotone" /></template>
<style>
.d3e0_z3po {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm.563-2l-.379-2.017a1 1 0 0 1 .799-1.167l14.034-2.632a1 1 0 0 1 1.167.799l.194 1.034a1 1 0 0 1-.798 1.167zm4.77-4l.563 3m4.77-4l.563 3M10 15v-2.5c0-.22.24-.356.429-.243l4.142 2.486a.3.3 0 0 1 0 .514l-4.142 2.486A.283.283 0 0 1 10 17.5z");
}

.ft5dv1b6b {
  fill: none;
}

.su516sdxu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.201 7.167a2 2 0 0 1 1.598-2.334l14.034-2.632a2 2 0 0 1 2.334 1.598l.194 1.034a2 2 0 0 1-1.597 2.334L14.322 8H19a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-8c0-.642.205-1.266.586-1.783l-.006-.033Z");
}

</style>
