<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pvphdqbpg"/><path class="hwt2nkbij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:joystick-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hwt2nkbij {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 15h18v6H3Zm4 0v-2m5 2V9M9 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.pvphdqbpg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 9a3 3 0 1 1 0-6a3 3 0 0 1 0 6m9 12H3v-6h18Z");
}

</style>
