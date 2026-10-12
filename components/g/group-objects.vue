<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dk6evxs2f"/><rect class="utrj8tbjg"/><circle class="ux15onb8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:group-objects" /></template>
<style>
.dk6evxs2f {
  d: path("M2.75 6.5V4.25a1.5 1.5 0 0 1 1.5-1.5H6.5m11 0h2.25a1.5 1.5 0 0 1 1.5 1.5V6.5m0 11v2.25a1.5 1.5 0 0 1-1.5 1.5H17.5m-11 0H4.25a1.5 1.5 0 0 1-1.5-1.5V17.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.utrj8tbjg {
  width: 5.5px;
  height: 5.5px;
  x: 6.25px;
  y: 6.25px;
  rx: 1.25px;
}

.ux15onb8l {
  cx: 15.5px;
  cy: 15.5px;
  r: 2.75px;
}

</style>
