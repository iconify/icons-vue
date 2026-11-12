<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m057llm6s"/><path class="a9za60eld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kite-duotone" /></template>
<style>
.a9za60eld {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 13l-4 4a1.414 1.414 0 0 1-2 0L3 9l9-6l9 6zm-5-9v13M4 9h16m-8 9c0 3 5 3 7 3");
}

.ft5dv1b6b {
  fill: none;
}

.m057llm6s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.707 17.707a2.414 2.414 0 0 1-3.414 0l-8-8a.998.998 0 0 1 .152-1.539l9-6a1 1 0 0 1 1.11 0l9 6a.998.998 0 0 1 .152 1.539Z");
}

</style>
