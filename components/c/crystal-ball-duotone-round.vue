<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="aeijmimxi"/><path class="w29_zcc8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crystal-ball-duotone-round" /></template>
<style>
.aeijmimxi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18.821 16.615A3.002 3.002 0 0 1 17 22H7a3 3 0 0 1-1.821-5.385c-2.076-2.424-2.623-5.717-1.554-8.713a8.893 8.893 0 0 1 15.538-2.299a9.2 9.2 0 0 1 1.731 4.845a8.63 8.63 0 0 1-2.073 6.167");
}

.ft5dv1b6b {
  fill: none;
}

.w29_zcc8r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 17C1.262 12.302 4.584 3 12 3s10.738 9.302 5 14M5 19a2 2 0 0 1 2-2h10a2 2 0 1 1 0 4H7a2 2 0 0 1-2-2m4-9a3 3 0 0 1 3-3");
}

</style>
