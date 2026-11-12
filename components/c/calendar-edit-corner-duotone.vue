<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="buyhhp4jy"/><path class="d169sbc7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-edit-corner-duotone" /></template>
<style>
.buyhhp4jy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 9a2 2 0 0 0-2 2v10H6a2 2 0 0 1-2-2V9Zm2 9l5-5l3 3l-5 5h-3Z");
}

.d169sbc7b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21H6a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v2M8 3v2m8-2v2M4 9h16m-7 12v-3l5-5l3 3l-5 5Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
