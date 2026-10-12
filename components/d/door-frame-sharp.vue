<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ylinnnb_x"/><path class="vrkj-9b6f"/><path class="t1yeywbfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:door-frame-sharp" /></template>
<style>
.t1yeywbfb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 14.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vrkj-9b6f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 7.75h5.5v13.5h-5.5z");
}

.ylinnnb_x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 20.5V2.75h15.5v18.5H17V5.5H7v15.75H4.25z");
}

</style>
