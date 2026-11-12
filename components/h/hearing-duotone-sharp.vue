<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k8h6mbb2v"/><path class="mxdr0qj2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hearing-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k8h6mbb2v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 18V9a7 7 0 1 1 14 0c0 1.529-.372 3.012-1.326 4.23c-.71.906-1.629 1.536-2.582 2.155c-.533.347-1.147.724-1.571 1.203c-.364.411-.521.864-.521 1.412a3.98 3.98 0 0 1-1.172 2.828A3.998 3.998 0 0 1 2 18");
}

.mxdr0qj2b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9a6 6 0 1 1 12 0c0 6-6 5-6 9a3 3 0 0 1-6 0m8-9a2 2 0 1 0-4 0c2 0 2 3 0 3m12-8a8.6 8.6 0 0 1 0 10");
}

</style>
