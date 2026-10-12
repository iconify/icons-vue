<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="u782pnb2p"/><path class="i9c8q2ykj"/><path class="fwu33tbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jump-rope-sharp" /></template>
<style>
.fwu33tbty {
  d: path("M8 13.25c-4-3-4-10.5 4-10.5s8 7.5 4 10.5M5.5 21h3m7 0h3");
}

.i9c8q2ykj {
  d: path("M12 10.5V15m-4-1.75L12 11l4 2.25M12 15l-2.5 2l1.5 2.5m1-4.5l2.5 2l-1.5 2.5");
}

.u782pnb2p {
  cx: 12px;
  cy: 7.25px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
