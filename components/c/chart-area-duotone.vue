<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yyx28koeg"/><path class="wunaiik9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-area-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.wunaiik9b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14v-2l2-2a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 0 2 0l4-4c.369-.369 1-.369 1 0v8a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1zM3 4v14a2 2 0 0 0 2 2h16");
}

.yyx28koeg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m7 12l2-2a1.415 1.415 0 0 1 2 0l1 1a1.415 1.415 0 0 0 2 0l4-4c.369-.369 1-.369 1 0v8a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1Z");
}

</style>
