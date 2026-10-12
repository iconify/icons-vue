<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yceyyxb5e"/><path class="ivdr8mbot"/><rect class="il8p-j2nc"/><rect class="rdfjt3bak"/><path class="c-od-jb3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:confusion-matrix" /></template>
<style>
.c-od-jb3j {
  d: path("M2.75 7.5V11M7.5 2.75H11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.il8p-j2nc {
  width: 3px;
  height: 3px;
  x: 7.75px;
  y: 7.75px;
  rx: 1px;
}

.ivdr8mbot {
  d: path("M13.25 5.25v16m-8-8h16");
}

.rdfjt3bak {
  width: 3px;
  height: 3px;
  x: 15.75px;
  y: 15.75px;
  rx: 1px;
}

.yceyyxb5e {
  width: 16px;
  height: 16px;
  x: 5.25px;
  y: 5.25px;
  rx: 2px;
}

</style>
