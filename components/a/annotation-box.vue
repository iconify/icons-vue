<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c5j8a5b0c"/><rect class="d646m-7-c"/><rect class="yyx4tq9ph"/><rect class="w3dsgdb0e"/><rect class="eoo4cabcd"/><rect class="z4x6mo8me"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:annotation-box" /></template>
<style>
.c5j8a5b0c {
  d: path("M7.5 4.5h9m-9 15h9m-12-12v9m15-9v9");
}

.d646m-7-c {
  width: 3.5px;
  height: 3.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1px;
}

.eoo4cabcd {
  width: 3.5px;
  height: 3.5px;
  x: 17.75px;
  y: 17.75px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w3dsgdb0e {
  width: 3.5px;
  height: 3.5px;
  x: 2.75px;
  y: 17.75px;
  rx: 1px;
}

.yyx4tq9ph {
  width: 3.5px;
  height: 3.5px;
  x: 17.75px;
  y: 2.75px;
  rx: 1px;
}

.z4x6mo8me {
  width: 7.5px;
  height: 3.5px;
  x: 8.25px;
  y: 10.25px;
  rx: 1.25px;
}

</style>
