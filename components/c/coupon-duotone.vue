<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c_445igfv"/><path class="i-efbtb6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coupon-duotone" /></template>
<style>
.c_445igfv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 8v1a3 3 0 1 0 0 6v1a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-1a3 3 0 1 0 0-6V8a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2");
}

.ft5dv1b6b {
  fill: none;
}

.i-efbtb6k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 9V8a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v1a3 3 0 0 1 0 6v1a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-1a3 3 0 0 1 0-6m-7 1l-4 4M9 9h.01M15 15h.01");
}

</style>
