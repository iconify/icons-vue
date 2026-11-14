<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oip2nqb8v"/><path class="h0gupvbad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campus-mailroom" /></template>
<style>
.h0gupvbad {
  d: path("M10.5 17.5v-7A3.5 3.5 0 0 0 7 7m6.5 10.5v4m3-14.5V2.75m1.125 0h.75A1.125 1.125 0 0 1 19.5 3.875A1.125 1.125 0 0 1 18.375 5h-.75A1.125 1.125 0 0 1 16.5 3.875a1.125 1.125 0 0 1 1.125-1.125");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oip2nqb8v {
  d: path("M7 7h10a3.5 3.5 0 0 1 3.5 3.5v7h-17v-7A3.5 3.5 0 0 1 7 7");
}

</style>
