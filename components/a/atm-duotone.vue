<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nmqlkxwwa"/><path class="aaqvznb_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:atm-duotone" /></template>
<style>
.aaqvznb_h {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v12M7 6h10M3 10h4m10 0h4M7 10h10v9a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2zm3 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.ft5dv1b6b {
  fill: none;
}

.nmqlkxwwa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 9a1 1 0 0 1 1 1v9a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3v-9a1 1 0 0 1 1-1Z");
}

</style>
