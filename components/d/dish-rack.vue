<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qehdn1bxs"/><path class="gv3caxbxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dish-rack" /></template>
<style>
.gv3caxbxq {
  d: path("M5.5 10A1.25 5 0 1 0 8 10a1.25 5 0 1 0-2.5 0m5.25 0a1.25 5 0 1 0 2.5 0a1.25 5 0 1 0-2.5 0M16 10a1.25 5 0 1 0 2.5 0a1.25 5 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qehdn1bxs {
  d: path("M5.125 15h13.75a2.625 2.625 0 0 1 2.625 2.625v.25a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 17.875v-.25A2.625 2.625 0 0 1 5.125 15");
}

</style>
