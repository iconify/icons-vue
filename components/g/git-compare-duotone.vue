<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e08jvybqs"/><path class="akbvnry6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-compare-duotone" /></template>
<style>
.akbvnry6w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m14 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2-2V8a2 2 0 0 0-2-2h-6m3-3l-3 3l3 3M5 8v8a2 2 0 0 0 2 2h6m-3-3l3 3l-3 3");
}

.e08jvybqs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.236 4.832A3 3 0 1 1 7.763 7.17a3 3 0 0 1-5.527-2.338m14 12a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338");
}

.ft5dv1b6b {
  fill: none;
}

</style>
