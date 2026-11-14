<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kudlb8kcj"/><path class="f_p7hpaxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emergency-drill" /></template>
<style>
.f_p7hpaxh {
  d: path("M7.75 15a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kudlb8kcj {
  d: path("M9.5 9.5H21v4h-6.25a5.5 5.5 0 1 1-5.25-4m-7-4.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m3.25 2L7 10");
}

</style>
