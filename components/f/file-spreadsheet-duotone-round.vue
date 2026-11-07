<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b6fkvxgfa"/><path class="v4go4nuhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-spreadsheet-duotone-round" /></template>
<style>
.b6fkvxgfa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19.707 8.293A1 1 0 0 1 20 9v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5h4c.265 0 .52.105.707.293ZM13 7a2 2 0 0 0 2 2h3l-5-5Z");
}

.ft5dv1b6b {
  fill: none;
}

.v4go4nuhi {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H9a4 4 0 0 0-4 4v10a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4V9m-6-6l6 6m-6-6v4a2 2 0 0 0 2 2h4M8 13a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1Zm0 2h8m-5-3v6");
}

</style>
