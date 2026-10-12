<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="b1_jsmbhw"/><path class="z-17y3bzc"/><circle class="xe3kkrg5a"/><path class="xpec6eu_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:av-receiver" /></template>
<style>
.b1_jsmbhw {
  width: 18.5px;
  height: 10.5px;
  x: 2.75px;
  y: 6.25px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xe3kkrg5a {
  cx: 16.5px;
  cy: 11.5px;
  r: 2.25px;
}

.xpec6eu_k {
  d: path("M5.75 16.75v2m12.5-2v2");
}

.z-17y3bzc {
  d: path("M6.25 9.75h5m-5 3.5h3");
}

</style>
