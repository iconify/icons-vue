<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k61eikb2h"/><path class="klp7oybbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clapperboard-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k61eikb2h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.201 7.167a2 2 0 0 1 1.598-2.334l14.034-2.632a2 2 0 0 1 2.334 1.598l.194 1.034a2 2 0 0 1-1.597 2.334L14.322 8H17a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5v-4c0-1.135.381-2.232 1.091-3.118a1 1 0 0 1-.511-.698Z");
}

.klp7oybbo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 13a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm.563-4l-.379-2.017a1 1 0 0 1 .799-1.167l14.034-2.632a1 1 0 0 1 1.167.799l.194 1.034a1 1 0 0 1-.798 1.167zm4.77-4l.563 3m4.77-4l.563 3M10 15v-2.5c0-.22.24-.356.429-.243l4.142 2.486a.3.3 0 0 1 0 .514l-4.142 2.486A.283.283 0 0 1 10 17.5z");
}

</style>
