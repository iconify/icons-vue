<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo6jxacxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:graduated-scale" /></template>
<style>
.mo6jxacxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.125 2.5h3.75A2.625 2.625 0 0 1 16.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-3.75A2.625 2.625 0 0 1 7.5 18.875V5.125A2.625 2.625 0 0 1 10.125 2.5M7.5 6.5h5m-5 4h3m-3 4h5m-5 4h3");
}

</style>
