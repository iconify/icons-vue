<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qzkvbx_uy"/><path class="av9_2ac3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:library-card" /></template>
<style>
.av9_2ac3m {
  d: path("M5.5 9.25c1.4-.6 2.6-.5 3.5.35c.9-.85 2.1-.95 3.5-.35V15c-1.4-.6-2.6-.5-3.5.35c-.9-.85-2.1-.95-3.5-.35Zm9 0h4m-4 2.75h4m-4 2.75H17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qzkvbx_uy {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 2px;
}

</style>
