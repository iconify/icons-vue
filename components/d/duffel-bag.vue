<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="e3cp3cbtq"/><path class="wg0ngdt6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:duffel-bag" /></template>
<style>
.e3cp3cbtq {
  width: 18.5px;
  height: 10.75px;
  x: 2.75px;
  y: 9.75px;
  rx: 4.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wg0ngdt6m {
  d: path("M6.5 9.75C6.5 6.5 9 4.5 12 4.5s5.5 2 5.5 5.25m-8 0c0-1.5 1.1-2.5 2.5-2.5s2.5 1 2.5 2.5m-5 3h5M7 10c-1.5 2-1.5 8.25 0 10.25M17 10c1.5 2 1.5 8.25 0 10.25");
}

</style>
