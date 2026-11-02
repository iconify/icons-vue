<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="curcdctaz"/><path class="k6c3jrtaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-open-duotone" /></template>
<style>
.curcdctaz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 22H5a3 3 0 0 1-3-3V9a1 1 0 0 1 .445-.832l6-4a6.41 6.41 0 0 1 7.11 0l6 4A1 1 0 0 1 22 9v10a3 3 0 0 1-3 3");
}

.ft5dv1b6b {
  fill: none;
}

.k6c3jrtaw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21H5a2 2 0 0 1-2-2V9l6-4a5.41 5.41 0 0 1 6 0l6 4v10a2 2 0 0 1-2 2zM3 9l5 5c.64.64 1.36 1 2 1h4c.64 0 1.36-.36 2-1l5-5");
}

</style>
