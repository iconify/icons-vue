<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nguimjb5t"/><path class="o_r0cfbju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-check-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nguimjb5t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 10a1 1 0 0 1-1-1a5 5 0 0 1 1.464-3.536A4.98 4.98 0 0 1 8 4h8c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 21 9a1 1 0 0 1-1 1Z");
}

.o_r0cfbju {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21H8a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4M8 3v2m8-2v2M4 9h16m-7 8l3 3l5-6");
}

</style>
