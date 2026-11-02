<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qwg51fzsq"/><path class="bveq4kb6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-1-duotone-round" /></template>
<style>
.bveq4kb6e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 17v1a3 3 0 0 0 6 0v-5c0-1.28-.36-2.36-1-3l-4-4a4.243 4.243 0 0 0-6 0l-4 4c-.64.64-1 1.72-1 3v5a3 3 0 0 0 6 0v-1a2 2 0 1 1 4 0");
}

.ft5dv1b6b {
  fill: none;
}

.qwg51fzsq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 17v1a4 4 0 0 1-8 0v-5c0-1.317.335-2.748 1.293-3.707l4-4a5.243 5.243 0 0 1 7.414 0l4 4C20.665 10.252 21 11.683 21 13v5a4 4 0 0 1-8 0v-1a1 1 0 0 0-2 0");
}

</style>
