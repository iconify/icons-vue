<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="fxwn4ybqh"/><path class="h5dfnbb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hurdle" /></template>
<style>
.fxwn4ybqh {
  width: 17.5px;
  height: 4px;
  x: 3.25px;
  y: 5.75px;
  rx: 1.25px;
}

.h5dfnbb6c {
  d: path("M8.5 6L7 9.5M13 6l-1.5 3.5m6-3.5L16 9.5m-10.25.25v10.5m12.5-10.5v10.5m-15 0h5m7.5 0h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
