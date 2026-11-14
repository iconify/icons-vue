<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yzc30o_8q"/><path class="z963z9bsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cancer-ribbon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yzc30o_8q {
  d: path("M9 3C6 3 5.5 6.5 8 9.5l8 11");
}

.z963z9bsq {
  d: path("M15 3c3 0 3.5 3.5 1 6.5l-8 11");
}

</style>
