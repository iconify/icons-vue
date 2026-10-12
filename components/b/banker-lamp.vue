<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fpcn-jb1l"/><rect class="ekojufdim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:banker-lamp" /></template>
<style>
.ekojufdim {
  width: 11px;
  height: 3px;
  x: 6.5px;
  y: 18.25px;
  rx: 1.5px;
}

.fpcn-jb1l {
  d: path("m5.5 10.5l1-4q.25-1 1.25-1h8.5q1 0 1.25 1l1 4Zm6.5 0v7.75m4-7.75v2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
