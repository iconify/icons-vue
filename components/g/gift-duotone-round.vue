<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xj519vbuh"/><path class="ytd78-1lo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gift-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.xj519vbuh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 11v6a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4v-6a2 2 0 1 1 0-4h14a2 2 0 1 1 0 4");
}

.ytd78-1lo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9a2 2 0 0 1 2-2h14a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2m2 2v6a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4v-6m-7-4H9C7 7 6 6 6 5c0-2 2-2 3-1zm0 0h3c2 0 3-1 3-2c0-2-2-2-3-1zm0 0v14");
}

</style>
