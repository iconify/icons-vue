<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m71e-ip1v"/><path class="sxx5rpb_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-office-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m71e-ip1v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 21V7a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v14Z");
}

.sxx5rpb_k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 21V7a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v14M3 21h18M8 9v4m4-4v4m4-4v4m-6 8v-2a2 2 0 1 1 4 0v2");
}

</style>
