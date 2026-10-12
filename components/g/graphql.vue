<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ppksuyb0e"/><path class="wo_9c9o2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:graphql" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ppksuyb0e {
  d: path("m12.87 3l6.49 3.75q.87.5.87 1.5v7.5q0 1-.87 1.5L12.87 21q-.87.5-1.74 0l-6.49-3.75q-.87-.5-.87-1.5v-7.5q0-1 .87-1.5L11.13 3q.87-.5 1.74 0");
}

.wo_9c9o2g {
  d: path("m12.38 7.4l3.79 6.58q.38.65-.37.65H8.2q-.75 0-.37-.65l3.8-6.58q.37-.65.75 0");
}

</style>
