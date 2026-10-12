<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="c15actb7e"/><path class="pd2p9jbbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alms-bowl" /></template>
<style>
.c15actb7e {
  cx: 12px;
  cy: 4.5px;
  r: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pd2p9jbbw {
  d: path("M3.75 9C4.75 7 8 6 12 6s7.25 1 8.25 3Zm-.25 3h17c0 5.25-3.8 9.25-8.5 9.25s-8.5-4-8.5-9.25");
}

</style>
