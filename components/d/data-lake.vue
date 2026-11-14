<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pm-67_bax"/><path class="akee6bkib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-lake" /></template>
<style>
.akee6bkib {
  d: path("M7.5 8c1-1 2-1 3 0s2 1 3 0s2-1 3 0m-12 4c1-1 2-1 3 0s2 1 3 0s2-1 3 0s2 1 3 0s2-1 3 0m-12 4c1-1 2-1 3 0s2 1 3 0s2-1 3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pm-67_bax {
  d: path("M2.5 12a9.5 8 0 1 0 19 0a9.5 8 0 1 0-19 0");
}

</style>
