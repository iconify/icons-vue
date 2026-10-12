<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ajgh7eb0l"/><rect class="nvel9tbvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hair-straightener" /></template>
<style>
.ajgh7eb0l {
  d: path("m10.21 14.82l-.92.36q-.94.35-1.29-.59L4.45 5.22q-.35-.94.59-1.29l.92-.36q.94-.35 1.29.59l3.55 9.37q.35.94-.59 1.29m3.58 0l.92.36q.94.35 1.29-.59l3.55-9.37q.35-.94-.59-1.29l-.92-.36q-.94-.35-1.29.59l-3.55 9.37q-.35.94.59 1.29");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nvel9tbvv {
  width: 5px;
  height: 4px;
  x: 9.5px;
  y: 17.25px;
  rx: 1.5px;
}

</style>
