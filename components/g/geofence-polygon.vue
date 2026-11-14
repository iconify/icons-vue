<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="puksyf0ns"/><path class="k1r6rk9xf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:geofence-polygon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k1r6rk9xf {
  d: path("M12 17c-1.25-1.25-3.25-3.5-3.25-6.25a3.25 3.25 0 0 1 6.5 0c0 2.75-2 5-3.25 6.25m0-6.25h.01");
}

.puksyf0ns {
  d: path("m3.278 6.944l5.591-3.993a1.75 1.75 0 0 1 1.389-.286l9.424 2.048a1.75 1.75 0 0 1 1.377 1.635l.395 9.101a1.75 1.75 0 0 1-.861 1.584l-6.853 4.032a1.75 1.75 0 0 1-1.537.116l-8.161-3.264a1.75 1.75 0 0 1-1.098-1.538l-.396-7.924a1.75 1.75 0 0 1 .73-1.511");
}

</style>
