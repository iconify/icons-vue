<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><path class="xqa9mabnr"/><path class="kw-10cd_g"/><path class="tyba--flk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:capsule-window-sharp" /></template>
<style>
.kw-10cd_g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 15.75a10 10 0 0 1 7.5-3.5v3.5h-1Z");
}

.tyba--flk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 9.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xqa9mabnr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 6h9v12H6V6z");
}

.ywno-sh7h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

</style>
