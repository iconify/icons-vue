<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qo-6rjj_p"/><path class="xsg5cr3sf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qo-6rjj_p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19.823 19.823A2 2 0 0 1 18 21H6a2.003 2.003 0 0 1-2-2V9h5ZM15 9h5v5Z");
}

.xsg5cr3sf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.823 19.823A2 2 0 0 1 18 21H6a2 2 0 0 1-2-2V7a2 2 0 0 1 1.177-1.823M11 5h7a2 2 0 0 1 2 2v7M4 9h5m6 0h5m-4-6v2M2 2l20 20");
}

</style>
