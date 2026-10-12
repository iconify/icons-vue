<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bz993_bbi"/><path class="g93rzkbmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:game-controller-sharp" /></template>
<style>
.bz993_bbi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 5.25h9l3.184-.002l.716 3.102l.8 7.9a2.5 2.5 0 0 1-4.3 2.2l-2.7-3.2H9.8l-2.7 3.2a2.5 2.5 0 0 1-4.3-2.2l.8-7.9l.716-3.102zM6 10h3M7.5 8.5v3");
}

.g93rzkbmy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 7.6h.01m1.59 1.6h.01m-1.61 1.6h.01m-1.61-1.6h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
