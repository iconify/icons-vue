<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v7g_znbsq"/><path class="snvnvacmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cloud-upload" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.snvnvacmr {
  d: path("M12 15.85V10.6m-2.25 2.25L12 10.6l2.25 2.25");
}

.v7g_znbsq {
  d: path("M6.75 18.35a4 4 0 0 1-.55-7.96A5.75 5.75 0 0 1 16.85 9a4.5 4.5 0 0 1-.6 9.35Z");
}

</style>
