<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s2b_s4nbl"/><rect class="v0603bajz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:graduated-cylinder" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s2b_s4nbl {
  d: path("M8.25 4.25a1.5 1.5 0 0 1 1.5-1.5h4.5a1.5 1.5 0 0 1 1.5 1.5V18.5h-7.5Zm0 3h3.5m-3.5 3.5h2.25m-2.25 3.5h3.5");
}

.v0603bajz {
  width: 12.5px;
  height: 2.75px;
  x: 5.75px;
  y: 18.5px;
  rx: 1.25px;
}

</style>
