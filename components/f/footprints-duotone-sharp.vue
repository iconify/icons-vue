<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jktn47bgr"/><path class="z45q14lze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:footprints-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jktn47bgr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 20h-5a1 1 0 0 1-1-1v-5a5.1 5.1 0 0 0-.261-1.621c-.259-.775-.68-1.482-1.017-2.223C13.26 9.138 13 8.131 13 7a6.1 6.1 0 0 1 .245-1.756C13.912 3.023 15.757 2 18 2c1.16 0 2.281.314 3.031 1.25C21.855 4.281 22 5.727 22 7v12a1 1 0 0 1-1 1M2 9c0-1.273.145-2.719.969-3.75C3.719 4.314 4.84 4 6 4c2.243 0 4.088 1.023 4.755 3.244A6.1 6.1 0 0 1 11 9c0 1.131-.26 2.138-.722 3.156c-.337.741-.758 1.448-1.017 2.223A5.1 5.1 0 0 0 9 16v5a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.z45q14lze {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17V9c0-3 1-4 3-4c3 0 4 2 4 4c0 3-2 4-2 7v5H3zm18-2V7c0-3-1-4-3-4c-3 0-4 2-4 4c0 3 2 4 2 7v5h5zM3 17h5m13-2h-5");
}

</style>
