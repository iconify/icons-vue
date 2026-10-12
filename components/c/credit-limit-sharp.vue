<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mss0wg22n"/><path class="vrxzsk89v"/><path class="qhx66-4er"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:credit-limit-sharp" /></template>
<style>
.mss0wg22n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5v14.5H2.75zm0 4.25h18.5M6.5 14.5H12");
}

.qhx66-4er {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 12.5v4");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vrxzsk89v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 14.5h.01");
}

</style>
