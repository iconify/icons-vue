<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zn12e4o2k"/><path class="wi0qlkb1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:droplet-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.wi0qlkb1y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3S5 8 5 14a7 7 0 0 0 14 0c0-6-7-11-7-11m3 11a3 3 0 0 1-3 3");
}

.zn12e4o2k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 3s7 5 7 11a7 7 0 1 1-14 0c0-6 7-11 7-11");
}

</style>
