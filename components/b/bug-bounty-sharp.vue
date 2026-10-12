<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="znhfc6o7n"/><circle class="upu83lbfh"/><path class="v-7kp1bup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bug-bounty-sharp" /></template>
<style>
.upu83lbfh {
  cx: 17px;
  cy: 17px;
  r: 4.25px;
}

.v-7kp1bup {
  d: path("M18.25 15.5h-2.5V17h2.5v1.5h-2.5M17 14.75v.75m0 3v.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.znhfc6o7n {
  d: path("M5 6.25h8.5v11H5zm2 0a2.25 2.25 0 0 1 4.5 0M5 10H2.75M5 13.5H2.75M13.5 10h2.25m-6.5-.5v6");
}

</style>
