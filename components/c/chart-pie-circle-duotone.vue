<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mntdggbts"/><path class="dkkg_gbvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pie-circle-duotone" /></template>
<style>
.dkkg_gbvz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12a9 9 0 1 0-9 9v-9zm-6 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.ft5dv1b6b {
  fill: none;
}

.mntdggbts {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 13h-8v8a1 1 0 0 1-1 1a10 10 0 1 1 10-10a1 1 0 0 1-1 1");
}

</style>
