<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g4jo93baq"/><path class="t7ytmab8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:doorbell-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g4jo93baq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 3h12v18H6Z");
}

.t7ytmab8v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 3h12v18H6Zm4 5h4m-4 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
