<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="itls3g7-o"/><path class="yjid82o_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:layout-responsive" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.itls3g7-o {
  d: path("M11 14.5H4.5a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2");
}

.yjid82o_u {
  d: path("M16.625 8.5h2.25a2.625 2.625 0 0 1 2.625 2.625v7.25A2.625 2.625 0 0 1 18.875 21h-2.25A2.625 2.625 0 0 1 14 18.375v-7.25A2.625 2.625 0 0 1 16.625 8.5M7 14.5v4m-2.5 0h5m7.25-.5h2");
}

</style>
