<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y0d0jm-jr"/><path class="gik0cutna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-archive-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gik0cutna {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H5v18M19 9v12h-4M13 3l6 6m-6-6v6h6m-9-3h.01M8 8h.01M10 10h.01M8 12h.01M10 16a2 2 0 0 1 2 2v2a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-2a2 2 0 0 1 2-2");
}

.y0d0jm-jr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 18V3h8l.034.034q-.01-.01-.022-.004a.02.02 0 0 0-.012.018V9h5.952a.02.02 0 0 0 .018-.012q.006-.012-.004-.022L19 9v12h-4v-3a5 5 0 0 0-10 0");
}

</style>
