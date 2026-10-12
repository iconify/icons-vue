<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rszr70bwc"/><path class="o8yd5p_pg"/><path class="gxf0_bc0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flute-sharp" /></template>
<style>
.gxf0_bc0u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.17 15.37l2.47 2.47");
}

.o8yd5p_pg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.94 13.06h.01m2.11-2.12h.01m2.11-2.12h.01");
}

.rszr70bwc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.47 17.06L17.06 4.47l1.06-1.06l1.06 1.06l.35.35l1.06 1.06l-1.06 1.06L6.94 19.53l-1.06 1.06l-1.06-1.06l-.35-.35l-1.06-1.06z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
