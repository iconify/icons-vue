<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nguimjb5t"/><path class="mfy4cdcre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mfy4cdcre {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 9a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v8a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm0 0h16M8 3v2m8-2v2");
}

.nguimjb5t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 10a1 1 0 0 1-1-1a5 5 0 0 1 1.464-3.536A4.98 4.98 0 0 1 8 4h8c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 21 9a1 1 0 0 1-1 1Z");
}

</style>
