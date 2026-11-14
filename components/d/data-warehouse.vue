<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i7r0qib2l"/><path class="wu04qx7_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-warehouse" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7r0qib2l {
  d: path("m4.363 8.993l6.75-3.971a1.75 1.75 0 0 1 1.774 0l6.75 3.971a1.75 1.75 0 0 1 .863 1.508v8.249a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75v-8.249a1.75 1.75 0 0 1 .863-1.508");
}

.wu04qx7_l {
  d: path("M9 12h6a1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 19v-5.5A1.5 1.5 0 0 1 9 12m-1.5 2.75h9m-9 2.75h9");
}

</style>
