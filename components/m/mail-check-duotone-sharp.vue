<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vqz-w8bqr"/><path class="qwh6o3h8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-check-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qwh6o3h8o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 13v6H3V5h8M3 5l6 6h4m2-5l2 2l4-4");
}

.vqz-w8bqr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M22 19a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h8a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779c.52 1.556 1.603 2.735 3.003 3.551c1.093.638 2.364 1.031 3.638.985a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13Z");
}

</style>
