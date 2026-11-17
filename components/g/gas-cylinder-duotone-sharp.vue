<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lzv1jp8_x"/><path class="fi9bmkcps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gas-cylinder-duotone-sharp" /></template>
<style>
.fi9bmkcps {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 19H4v-8a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4zM8 19v2h8v-2M4 13h16M8 7V3h8v4");
}

.ft5dv1b6b {
  fill: none;
}

.lzv1jp8_x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 3h8v4a4 4 0 0 1 4 4v8h-4v2H8v-2H4v-8a4 4 0 0 1 4-4Z");
}

</style>
