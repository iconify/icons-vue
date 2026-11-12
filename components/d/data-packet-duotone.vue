<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xh9_w6_ln"/><path class="a-0-r0bvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:data-packet-duotone" /></template>
<style>
.a-0-r0bvr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 7a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2Zm0 2h12m-8 4v3m4-3v3M3 8h2m-2 4h2m-2 4h2");
}

.ft5dv1b6b {
  fill: none;
}

.xh9_w6_ln {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 4h8a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3h-8a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3");
}

</style>
