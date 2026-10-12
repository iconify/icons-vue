<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="du7tf3bce"/><path class="q_sgb4nim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-key" /></template>
<style>
.du7tf3bce {
  width: 8.5px;
  height: 11px;
  x: 7.75px;
  y: 2.75px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q_sgb4nim {
  d: path("M10 6.75h4m-4 3h4m-2 4v7.5M12 17h2.25M12 20h2.25");
}

</style>
