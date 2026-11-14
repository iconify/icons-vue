<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bsoyd5b1r"/><path class="k2j_68bqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camp-blanket" /></template>
<style>
.bsoyd5b1r {
  d: path("M5.5 5h12L21 8.5V11H5.5a3 3 0 0 1 0-6m0 8.75H21v6H5.5a3 3 0 0 1 0-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2j_68bqp {
  d: path("M17.5 5v3.5H21M14 5v6m0 2.75v6");
}

</style>
