<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="py3zzgb9s"/><path class="ar-ejfdfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-duotone" /></template>
<style>
.ar-ejfdfk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 13V7a2 2 0 1 1 4 0V5a2 2 0 1 1 4 0v3a2 2 0 1 1 4 0v8a5 5 0 0 1-5 5h-4c-.64 0-1.36-.36-2-1l-6-6c-2-2 1-5 3-3zm4-6v5m4-4v4");
}

.ft5dv1b6b {
  fill: none;
}

.py3zzgb9s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 13V7a2 2 0 0 1 2-2l2 2V5a2 2 0 1 1 4 0v1h2a2 2 0 0 1 2 2v8a5 5 0 0 1-5 5h-4c-.763 0-1.479-.48-2-1l-6-6c-1.997-2.003.997-4.997 3-3Z");
}

</style>
