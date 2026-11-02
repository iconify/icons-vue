<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e5ei74bkw"/><path class="vwi6pzbgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hourglass-duotone" /></template>
<style>
.e5ei74bkw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 2a1 1 0 0 1 1 1v3c0 1.039-.578 1.992-1.293 2.707L13.414 12l3.293 3.293C17.422 16.008 18 16.961 18 18v3a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-3c0-1.039.578-1.992 1.293-2.707L10.586 12L7.293 8.707C6.578 7.992 6 7.039 6 6V3a1 1 0 0 1 1-1Z");
}

.ft5dv1b6b {
  fill: none;
}

.vwi6pzbgm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3v3c0 .64.36 1.36 1 2l4 4l-4 4c-.64.64-1 1.36-1 2v3M17 3v3c0 .64-.36 1.36-1 2l-4 4l4 4c.64.64 1 1.36 1 2v3M5 3h14M5 21h14");
}

</style>
