<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nq_e_2b0z"/><rect class="nzx-9lahs"/><path class="iwhulrnfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fence-wooden" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iwhulrnfp {
  d: path("M6.75 6.5v.01m10.5-.01v.01M2.75 10h18.5m-18.5 5.75h18.5");
}

.nq_e_2b0z {
  width: 3.5px;
  height: 17.75px;
  x: 5px;
  y: 3.5px;
  rx: 1px;
}

.nzx-9lahs {
  width: 3.5px;
  height: 17.75px;
  x: 15.5px;
  y: 3.5px;
  rx: 1px;
}

</style>
