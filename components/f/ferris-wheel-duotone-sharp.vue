<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a_gry6b2y"/><path class="szxnuxb1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ferris-wheel-duotone-sharp" /></template>
<style>
.a_gry6b2y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 12a2 2 0 1 1-.001-3.999A2 2 0 0 1 12 12");
}

.ft5dv1b6b {
  fill: none;
}

.szxnuxb1b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 10a7 7 0 1 0 14 0a7 7 0 0 0-14 0m7 2l-6 9m6-9l6 9M4 21h16m-6-11h5m-9 0H5m-1 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m2.05-4.95a1 1 0 1 0 2 0a1 1 0 0 0-2 0m9.9 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0M18 10a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-8 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
