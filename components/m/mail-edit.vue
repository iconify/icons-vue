<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_ji0cbtm"/><path class="gw00l4bzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mail-edit" /></template>
<style>
.gw00l4bzg {
  d: path("m6 7.5l5 3.5l5-3.5m-.75 12.125l.155-.699a1.5 1.5 0 0 1 .404-.735l3.066-3.066a1.237 1.237 0 0 1 1.75 0a1.237 1.237 0 0 1 0 1.75l-3.066 3.066a1.5 1.5 0 0 1-.735.404l-.699.155a.733.733 0 0 1-.875-.875");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_ji0cbtm {
  d: path("M4.5 4h13a2 2 0 0 1 2 2v5.5H14l-3 5v.5H4.5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2");
}

</style>
