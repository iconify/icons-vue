<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r5rkxtbhm"/><path class="tum1skx4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ice-cube-nature" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r5rkxtbhm {
  d: path("m12.24 3.164l4.375 2.344A2.63 2.63 0 0 1 18 7.822v4.856a2.63 2.63 0 0 1-1.385 2.314l-4.375 2.344a2.63 2.63 0 0 1-2.48 0l-4.375-2.344A2.63 2.63 0 0 1 4 12.678V7.822a2.63 2.63 0 0 1 1.385-2.314L9.76 3.164a2.63 2.63 0 0 1 2.48 0");
}

.tum1skx4r {
  d: path("M4 6.25L11 10l7-3.75M11 10v8m7.5-1s1.75 2 1.75 3a1.75 1.75 0 0 1-3.5 0c0-1 1.75-3 1.75-3");
}

</style>
