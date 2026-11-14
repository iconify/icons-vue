<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m-9559bdj"/><path class="a--81zb-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:insurance-office" /></template>
<style>
.a--81zb-d {
  d: path("M7 13.25a5 5 0 0 1 10 0Zm5 0v3.5a1.5 1.5 0 0 1-3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-9559bdj {
  d: path("m4.138 9.475l6.75-5.559a1.75 1.75 0 0 1 2.224 0l6.75 5.559a1.75 1.75 0 0 1 .638 1.351v8.424A1.75 1.75 0 0 1 18.75 21H5.25a1.75 1.75 0 0 1-1.75-1.75v-8.424a1.75 1.75 0 0 1 .638-1.351");
}

</style>
