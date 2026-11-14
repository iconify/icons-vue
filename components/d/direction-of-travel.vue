<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tef6ty2cs"/><path class="zp_iseblh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:direction-of-travel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tef6ty2cs {
  d: path("M2.5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4 0c6 0 6.5-11.5 14-11.5");
}

.zp_iseblh {
  d: path("m17.5 3.5l3 3l-3 3");
}

</style>
