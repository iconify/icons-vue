<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wk4hkydoh"/><path class="yckxvub5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drill-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.wk4hkydoh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 6a2 2 0 0 1 2-2h8c.728 0 1.398.394 1.75 1.031Q14.874 5 15 5h2a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-2q-.126 0-.25-.031A2 2 0 0 1 13 10h-2v6a2 2 0 1 1 0 4H7a2 2 0 1 1 0-4v-6H5a2 2 0 0 1-2-2Z");
}

.yckxvub5k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm4 4v6m4-6v6m-6 2a2 2 0 0 1 2-2h4a2 2 0 1 1 0 4H7a2 2 0 0 1-2-2M15 5h2a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-2m3-2h3");
}

</style>
