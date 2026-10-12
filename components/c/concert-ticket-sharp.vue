<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zr7nq64od"/><circle class="b_nqqtobi"/><path class="l4pf74bqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:concert-ticket-sharp" /></template>
<style>
.b_nqqtobi {
  cx: 9px;
  cy: 14.25px;
  r: 1.5px;
}

.l4pf74bqn {
  d: path("M10.5 14.25v-5.5l2.5 1");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zr7nq64od {
  d: path("M2.75 7.75v-2h18.5V9.5a2.5 2.5 0 0 0 0 5v3.75H2.75V14.5a2.5 2.5 0 0 0 0-5Zm13.5 0v.75m0 3v1m0 3v.75");
}

</style>
