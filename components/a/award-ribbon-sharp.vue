<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ucu3l9h6l"/><circle class="u782pnb2p"/><path class="d-4s68bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:award-ribbon-sharp" /></template>
<style>
.d-4s68bnx {
  d: path("M10.9 9.1L7.75 20.75M13.1 9.1l3.15 11.65");
}

.u782pnb2p {
  cx: 12px;
  cy: 7.25px;
  r: 1.75px;
}

.ucu3l9h6l {
  d: path("M9.14 6.68L4.11 4.07L3 3.5V11l1.11-.57l5.03-2.61l1.11-.57zm5.72 0l5.03-2.61L21 3.5V11l-1.11-.57l-5.03-2.61l-1.11-.57z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
