<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="uyx5kebwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:abs-light" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uyx5kebwg {
  d: path("m5.5 14.5l1.75-5l1.75 5m-2.85-1.75h2.2m2.4 1.75v-5H12a1.25 1.25 0 0 1 0 2.5h-1.25h1.5a1.25 1.25 0 0 1 0 2.5ZM18 10c-.35-.35-.85-.5-1.35-.5c-.7 0-1.2.45-1.2 1.1c0 1.4 2.75.9 2.75 2.35c0 .7-.6 1.1-1.35 1.1c-.6 0-1.1-.2-1.45-.6");
}

</style>
