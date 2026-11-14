<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ceue_bbed"/><path class="pmnqoiz3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-ev-chargers" /></template>
<style>
.ceue_bbed {
  d: path("M15.596 15.636q-.286.118-.596.114h-1.5q-.085.003-.168-.009q-.084-.011-.165-.037q-.08-.025-.156-.064q-.075-.039-.143-.09t-.125-.112q-.059-.061-.106-.131t-.081-.148T12.5 15l-1.25-5.5H5v-6h8q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132q.07.069.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194T15 5.5l1.5 8.5q.039.233.005.467M2.5 5H5M2.5 8H5");
}

.pmnqoiz3v {
  d: path("M14 15.75c0 4.75-5 5.75-7.5 3.75c-1.5-1.25-1-4 1-4m12.5-1L16.5 19H19l-1 3l3.75-5h-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
