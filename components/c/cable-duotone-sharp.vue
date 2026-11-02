<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l3gr_knhu"/><path class="alizsk_fc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable-duotone-sharp" /></template>
<style>
.alizsk_fc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5h8v4H3Zm10 10h8v4h-8ZM5 3v2m4-2v2m6 14v2m4-2v2M7 9v3h10v3");
}

.ft5dv1b6b {
  fill: none;
}

.l3gr_knhu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1Zm10 10a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-8a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Z");
}

</style>
