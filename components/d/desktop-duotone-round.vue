<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nzua2_eda"/><path class="htcmevx-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:desktop-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.htcmevx-r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v5a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm0 5h16M9 20h6");
}

.nzua2_eda {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 12a1 1 0 0 1 1 1a5 5 0 0 1-1.464 3.536A4.98 4.98 0 0 1 16 18H8a4.98 4.98 0 0 1-3.536-1.464A5 5 0 0 1 3 13a1 1 0 0 1 1-1Z");
}

</style>
