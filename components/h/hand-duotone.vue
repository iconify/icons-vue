<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e8d5g65qk"/><path class="ar-ejfdfk"/></g>`;
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

.e8d5g65qk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 10.586V7a3 3 0 0 1 3-3c.265 0 .52.105.707.293l.318.318A3.001 3.001 0 0 1 18 5h1a3 3 0 0 1 3 3v8a6 6 0 0 1-6 6h-4c-1.039 0-1.992-.578-2.707-1.293l-6-6c-.945-.945-1.233-2.271-.653-3.492c.163-.343.384-.655.653-.922c.267-.269.579-.49.922-.653a3 3 0 0 1 2.364-.099c.425.167.806.43 1.128.752Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
