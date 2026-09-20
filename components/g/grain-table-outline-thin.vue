<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrwkhybyf"/><path class="x50q_4bdr"/><path class="rjnrdobeg"/><path class="hdjpn54jj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grain-table-outline-thin" /></template>
<style>
.hdjpn54jj {
  d: path("M9 15h9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rjnrdobeg {
  d: path("M5.5 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.x50q_4bdr {
  d: path("M3 10h18");
}

.zrwkhybyf {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
