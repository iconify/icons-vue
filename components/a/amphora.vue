<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ekq8oobvf"/><path class="p-nmuepmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:amphora" /></template>
<style>
.ekq8oobvf {
  d: path("M10 3h4v3c3.5 1.5 4.5 5 3.5 8.5c-.75 2.5-3.5 5-5.5 6.5c-2-1.5-4.75-4-5.5-6.5c-1-3.5 0-7 3.5-8.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p-nmuepmn {
  d: path("M10 4.75C7.5 4.75 6.25 6 6.75 8.5M14 4.75c2.5 0 3.75 1.25 3.25 3.75");
}

</style>
