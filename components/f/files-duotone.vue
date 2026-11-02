<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tuzhkdbcw"/><path class="mrds6kbep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:files-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mrds6kbep {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 6H5a2 2 0 0 0-2 2v11a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2v-8M8 6l5 5M8 6v4a1 1 0 0 0 1 1h4m-2-8h5m0 0l5 5m-5-5v4a1 1 0 0 0 1 1h4m0 0v8a2 2 0 0 1-2 2h-2");
}

.tuzhkdbcw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.707 10.293A1 1 0 0 1 14 11v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3h3c.265 0 .52.105.707.293ZM8 10a1 1 0 0 0 1 1h3L8 7Z");
}

</style>
