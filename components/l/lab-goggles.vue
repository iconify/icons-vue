<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="bxesc7gpz"/><rect class="yl447ob2x"/><rect class="p6b10nbjx"/><path class="poy6azjfj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lab-goggles" /></template>
<style>
.bxesc7gpz {
  width: 15.5px;
  height: 9.25px;
  x: 4.25px;
  y: 7.25px;
  rx: 4.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p6b10nbjx {
  width: 4px;
  height: 4.5px;
  x: 13.25px;
  y: 9.5px;
  rx: 2px;
}

.poy6azjfj {
  d: path("M4.25 11.75h-1.5m17 0h1.5");
}

.yl447ob2x {
  width: 4px;
  height: 4.5px;
  x: 6.75px;
  y: 9.5px;
  rx: 2px;
}

</style>
