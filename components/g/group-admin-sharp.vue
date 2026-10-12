<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="cy0xj6z4q"/><path class="pja290a8r"/><circle class="hovlgbc0r"/><path class="bcy15pb5n"/><circle class="mxe25qb8g"/><path class="kfeov-lxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:group-admin-sharp" /></template>
<style>
.bcy15pb5n {
  d: path("M17 14h4.25v-.75c0-1.9-1.1-3-2.5-3s-2.5 1.1-2.5 3V14z");
}

.cy0xj6z4q {
  cx: 5.25px;
  cy: 6.25px;
  r: 2.25px;
}

.hovlgbc0r {
  cx: 18.75px;
  cy: 6.25px;
  r: 2.25px;
}

.kfeov-lxg {
  d: path("M6.75 21.25H18v-.75c0-2.9-2.6-4.75-6-4.75S6 17.6 6 20.5v.75z");
}

.mxe25qb8g {
  cx: 12px;
  cy: 11.5px;
  r: 2px;
}

.pja290a8r {
  d: path("M3.5 14h4.25v-.75c0-1.9-1.1-3-2.5-3s-2.5 1.1-2.5 3V14z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
