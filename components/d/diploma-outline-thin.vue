<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fqi0-7bcf"/><path class="qds1w346b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:diploma-outline-thin" /></template>
<style>
.fqi0-7bcf {
  d: path("M4 8a3 3 0 0 0 0 6h16a3 3 0 0 0 0 -6Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qds1w346b {
  d: path("M10 14v6l2 -2 2 2v-6");
}

</style>
