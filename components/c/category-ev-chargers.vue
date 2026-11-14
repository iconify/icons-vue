<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ceue_bbed"/><path class="mm7jyokuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-ev-chargers" /></template>
<style>
.ceue_bbed {
  d: path("M15.596 15.636q-.286.118-.596.114h-1.5q-.085.003-.168-.009q-.084-.011-.165-.037q-.08-.025-.156-.064q-.075-.039-.143-.09t-.125-.112q-.059-.061-.106-.131t-.081-.148T12.5 15l-1.25-5.5H5v-6h8q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132q.07.069.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194T15 5.5l1.5 8.5q.039.233.005.467M2.5 5H5M2.5 8H5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mm7jyokuu {
  d: path("M14 15.75c0 4.75-5 5.75-7.5 3.75c-1.5-1.25-1-4 1-4m11.699.03l-1.932 2.483a.611.611 0 0 0 .483.987a.9.9 0 0 1 .855 1.186l-.105.314a.257.257 0 0 0 .449.235L21 18a.625.625 0 0 0-.5-1a.93.93 0 0 1-.891-1.197l.016-.053a.244.244 0 0 0-.426-.22");
}

</style>
