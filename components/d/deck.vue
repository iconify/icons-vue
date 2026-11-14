<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="to0iykbaz"/><path class="s03df9b0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deck" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s03df9b0k {
  d: path("M4.5 12.75v8.75m9-8.75v8.75M2.5 5h13m0 7.75H18V17h3.5v4.5m-19 0h19M6 5v6m3-6v6m3-6v6");
}

.to0iykbaz {
  fill: currentColor;
  d: path("M3.375 11h11.25a.875.875 0 0 1 .875.875a.875.875 0 0 1-.875.875H3.375a.875.875 0 0 1-.875-.875a.875.875 0 0 1 .875-.875");
}

</style>
