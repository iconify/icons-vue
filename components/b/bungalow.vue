<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vcxhg3blr"/><path class="hd42ibc_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bungalow" /></template>
<style>
.hd42ibc_r {
  d: path("M9.5 11.5V8L12 5.5L14.5 8v3.5m-4 10v-4h3v4m-7-6h1m9 0h1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcxhg3blr {
  d: path("m3.666 9.298l2.911-5.5A1.5 1.5 0 0 1 7.903 3h8.194a1.5 1.5 0 0 1 1.326.798l2.911 5.5a1.5 1.5 0 0 1-1.325 2.202H4.991a1.5 1.5 0 0 1-1.325-2.202M4 11.5v10h16v-10");
}

</style>
