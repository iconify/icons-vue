<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u2es9428x"/><path class="ap_cgmbbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eye-off-duotone-round" /></template>
<style>
.ap_cgmbbu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.76 16.76A9.75 9.75 0 0 1 3 12a9.74 9.74 0 0 1 4.24-4.76M12 6a9.75 9.75 0 0 1 9 6a9.8 9.8 0 0 1-1.073 1.927m-9.341-3.341a2 2 0 1 0 2.828 2.828M2 2l20 20");
}

.ft5dv1b6b {
  fill: none;
}

.u2es9428x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 6a9.75 9.75 0 0 1 9 6a9.8 9.8 0 0 1-1.073 1.927Zm-9 6a9.74 9.74 0 0 1 4.241-4.759l9.518 9.518A9.75 9.75 0 0 1 3 12");
}

</style>
