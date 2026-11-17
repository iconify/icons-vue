<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vzvyb9xud"/><path class="pvnxdd_9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hydrogen-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pvnxdd_9x {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 13a7 7 0 0 1 14 0v8H5zm7-7V3m-2 0h4m-5 8v6m6-6v6m-6-3h6");
}

.vzvyb9xud {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 13v8H5v-8a7 7 0 1 1 14 0");
}

</style>
