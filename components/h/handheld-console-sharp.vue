<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="toeeos4em"/><path class="b69m9zacd"/><path class="wxw3awbew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:handheld-console-sharp" /></template>
<style>
.b69m9zacd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 5.25h9v6.25h-9zm.25 10.5h3m-1.5-1.5v3");
}

.toeeos4em {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.75h12v18.5H5V2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wxw3awbew {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 16.75h.01m2.24-2h.01");
}

</style>
