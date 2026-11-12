<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w85zccbro"/><path class="p21p-tbxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-indent-increase-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p21p-tbxv {
  d: path("M4 9L6.5714 12L4 15");
}

.w85zccbro {
  d: path("M3 6H21M11 10H21M11 14H21M3 18H21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
