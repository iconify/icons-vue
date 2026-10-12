<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="gmstibmbn"/><path class="l6vp_8syr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drown-warning" /></template>
<style>
.gmstibmbn {
  cx: 12px;
  cy: 13.5px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6vp_8syr {
  d: path("m4.5 6.25l2.87 9.5c-.39-.25-.77-.5-1.54-.5c-1.54 0-1.54 1-3.08 1m16.75-10l-2.87 9.5c.39-.25.77-.5 1.54-.5c1.54 0 1.54 1 3.08 1m-18.5 4c1.54 0 1.54-1 3.08-1s1.54 1 3.08 1s1.54-1 3.08-1s1.54 1 3.08 1s1.54-1 3.08-1s1.54 1 3.08 1");
}

</style>
