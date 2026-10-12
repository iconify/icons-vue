<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="y_piwpb6h"/><path class="o2xd2zbhi"/><rect class="aedi20s9l"/><rect class="h4oq8tb_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-camera" /></template>
<style>
.aedi20s9l {
  width: 8px;
  height: 4.5px;
  x: 13.25px;
  y: 2.75px;
  rx: 2px;
}

.h4oq8tb_k {
  width: 9.5px;
  height: 9.5px;
  x: 11.75px;
  y: 11.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o2xd2zbhi {
  d: path("M6.25 18.25v-11A2.25 2.25 0 0 1 8.5 5h4.75");
}

.y_piwpb6h {
  width: 7px;
  height: 3px;
  x: 2.75px;
  y: 18.25px;
  rx: 1.5px;
}

</style>
