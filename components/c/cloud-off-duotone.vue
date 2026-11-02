<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d06hhzb4e"/><path class="xexuogcpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-off-duotone" /></template>
<style>
.d06hhzb4e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.26 8.045C6.794 6.596 7.715 5.283 9 4.408a6.17 6.17 0 0 1 4.398-1.022a6 6 0 0 1 2.151.755c2.147 1.246 3.217 3.547 3.415 5.951A5.002 5.002 0 0 1 18 20H7a6 6 0 0 1-.74-11.955");
}

.ft5dv1b6b {
  fill: none;
}

.xexuogcpz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 19H7A5 5 0 0 1 7 9c.074-.26-.093-.762 0-1m3-3c3.359-1.868 8 .242 8 6a4 4 0 0 1 4 4c0 .587.227.498 0 1M2 3l19 19");
}

</style>
