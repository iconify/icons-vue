<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z7v_o5bvb"/><path class="cj_c-2gkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:generate-image" /></template>
<style>
.cj_c-2gkq {
  d: path("m5.75 18.25l3.25-4l2.5 2.5l1.5-1.5l2.25 3m3.25-15.5q.33 2.42 2.75 2.75q-2.42.33-2.75 2.75q-.33-2.42-2.75-2.75q2.42-.33 2.75-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z7v_o5bvb {
  width: 14px;
  height: 13.5px;
  x: 2.75px;
  y: 7.75px;
  rx: 2.5px;
}

</style>
