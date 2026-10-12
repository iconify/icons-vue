<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cb2yuwq3j"/><path class="hm-bgfqny"/><path class="xvlspstxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dishwasher-sharp" /></template>
<style>
.cb2yuwq3j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h16.5v18.5H3.75zm0 4.5h16.5");
}

.hm-bgfqny {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xvlspstxg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 10.75h6m-6.25 4v3m3.25-3v3m3.25-3v3");
}

</style>
