<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m4b03h7wq"/><path class="vhjijt_vm"/><rect class="ig9ps7f6m"/><path class="x1e96mbnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:layers-photo" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ig9ps7f6m {
  width: 12.5px;
  height: 12.5px;
  x: 2.75px;
  y: 8.75px;
  rx: 2px;
}

.m4b03h7wq {
  d: path("M8.75 2.75h10.5a2 2 0 0 1 2 2v10.5");
}

.vhjijt_vm {
  d: path("M5.75 5.75h10.5a2 2 0 0 1 2 2v10.5");
}

.x1e96mbnt {
  d: path("m2.75 18.25l3.5-3.5l4 4m-1-1l1.25-1.25l3 3");
}

</style>
