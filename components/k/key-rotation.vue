<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="n9w-9db8r"/><path class="ar75qkbfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:key-rotation" /></template>
<style>
.ar75qkbfc {
  d: path("M11.5 12h5m-2 0v2M4.42 7.63a8.75 8.75 0 0 1 15.16 0m0-2.75v2.75h-2.75m2.75 8.74a8.75 8.75 0 0 1-15.16 0m0 2.75v-2.75h2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n9w-9db8r {
  cx: 8.5px;
  cy: 12px;
  r: 3px;
}

</style>
