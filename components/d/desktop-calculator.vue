<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ckyw7ybwl"/><path class="jw39zdbwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:desktop-calculator" /></template>
<style>
.ckyw7ybwl {
  d: path("M7.687 4h8.626a3.5 3.5 0 0 1 3.484 3.173l.844 9A3.5 3.5 0 0 1 17.157 20H6.843a3.5 3.5 0 0 1-3.484-3.827l.844-9A3.5 3.5 0 0 1 7.687 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jw39zdbwj {
  d: path("M9 6.75h6a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H9a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 6.75m-1.5 6h.01m2.99 0h.01m2.99 0h.01m2.99 0h.01m-9.01 4h.01m2.99 0h.01m2.99 0h.01m2.99 0h.01");
}

</style>
