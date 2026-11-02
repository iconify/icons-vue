<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hj9kkwbwe"/><path class="zz1cu7bvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caravan-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hj9kkwbwe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 4a5 5 0 0 1 5 5v7a3 3 0 0 1-3 3h-2.171a3 3 0 0 1-5.658 0H5a3 3 0 0 1-3-3V9a5 5 0 0 1 5-5ZM9.293 18.707l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0-.002-1.412l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 .002 1.412");
}

.zz1cu7bvo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 18H5a2 2 0 0 1-2-2V9a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v7a2 2 0 0 1-2 2h-3m-5-8a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1Zm1 8a2 2 0 1 0 4 0a2 2 0 0 0-4 0m9-3h4");
}

</style>
