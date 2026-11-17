<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="idjd9mb1n"/><path class="vwi6pzbgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hourglass-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.idjd9mb1n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 3h10v3c0 .763-.48 1.479-1 2l-4 4l-4-4c-.52-.521-1-1.237-1-2Zm1 13l4-4l4 4c.52.521 1 1.237 1 2v3H7v-3c0-.763.48-1.479 1-2");
}

.vwi6pzbgm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3v3c0 .64.36 1.36 1 2l4 4l-4 4c-.64.64-1 1.36-1 2v3M17 3v3c0 .64-.36 1.36-1 2l-4 4l4 4c.64.64 1 1.36 1 2v3M5 3h14M5 21h14");
}

</style>
