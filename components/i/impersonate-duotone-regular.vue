<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qhdq2dbof"/><path class="n8oxfwbbl"/><path class="ejfmpibyt"/><path class="zdn0azbfs"/><path class="bt921xbxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:impersonate-duotone-regular" /></template>
<style>
.bt921xbxy {
  d: path("M5 21a7 7 0 0 1 14 0");
}

.ejfmpibyt {
  d: path("M7 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.n8oxfwbbl {
  fill: currentColor;
  d: path("M11 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qhdq2dbof {
  fill: currentColor;
  d: path("M7 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zdn0azbfs {
  d: path("M11 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
