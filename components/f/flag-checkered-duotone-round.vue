<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vt0vt8btq"/><path class="k4s0hzbez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-checkered-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k4s0hzbez {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 15c6-3 10 3 16 0V4C14 7 10 1 4 4Zm0 0v6m0-11c6-3 10 3 16 0M9 4v10m6-9v10");
}

.vt0vt8btq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 15V4c0-.379.214-.725.553-.894a8.9 8.9 0 0 1 4.706-.947c.706.05 1.405.176 2.092.341c1.268.306 2.498.75 3.766 1.055c1.162.28 2.351.42 3.537.2a7.2 7.2 0 0 0 1.899-.649A1 1 0 0 1 21 4v11a1 1 0 0 1-.553.894a8.9 8.9 0 0 1-4.706.947a13 13 0 0 1-2.092-.341c-1.268-.306-2.498-.75-3.766-1.055c-1.162-.28-2.351-.42-3.537-.2a7.2 7.2 0 0 0-1.899.649A1 1 0 0 1 3 15");
}

</style>
