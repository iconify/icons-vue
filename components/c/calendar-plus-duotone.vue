<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ocsocob9f"/><path class="ku5iqdbgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-plus-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ku5iqdbgo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 7a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2Zm4-4v2m8-2v2M4 9h16M9 15h6m-3-3v6");
}

.ocsocob9f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 9h16v10a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2Z");
}

</style>
