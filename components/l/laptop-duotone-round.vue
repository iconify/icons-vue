<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ik2nsxbgl"/><path class="gcrehc-br"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:laptop-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gcrehc-br {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 16V8a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v8M3 18a2 2 0 0 1 2-2h14a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2");
}

.ik2nsxbgl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 16V8a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v8Z");
}

</style>
