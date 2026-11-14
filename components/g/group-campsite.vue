<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c0vkqmhop"/><path class="lxipt2j1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:group-campsite" /></template>
<style>
.c0vkqmhop {
  d: path("M2.5 15.5a4.75 7 0 0 1 9.5 0m0 0a4.75 7 0 0 1 9.5 0m-19 0h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lxipt2j1v {
  d: path("m5.5 15.5l1.75-4l1.75 4m6 0l1.75-4l1.75 4");
}

</style>
