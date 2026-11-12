<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gay5d-bcp"/><path class="rifsw5bvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-check-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gay5d-bcp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 9h16v8a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Z");
}

.rifsw5bvc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 9a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v8a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm4-6v2m8-2v2M4 9h16M9 15l2 2l4-4");
}

</style>
