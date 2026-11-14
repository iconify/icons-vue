<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zss0kibqg"/><path class="mgysgi41f"/><path class="po5hu0s_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cat-flap" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mgysgi41f {
  d: path("M9.25 12h5.5a1.75 1.75 0 0 1 1.75 1.75V17a1.75 1.75 0 0 1-1.75 1.75h-5.5A1.75 1.75 0 0 1 7.5 17v-3.25A1.75 1.75 0 0 1 9.25 12");
}

.po5hu0s_s {
  d: path("m7.5 12l1.75 4.25h5.5L16.5 12");
}

.zss0kibqg {
  d: path("M7.5 2.5h9A3.5 3.5 0 0 1 20 6v12a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 18V6a3.5 3.5 0 0 1 3.5-3.5m9 6h.01");
}

</style>
