<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bk4stbzxd"/><path class="eykzzpblx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beehive" /></template>
<style>
.bk4stbzxd {
  d: path("m7.75 4.75l3.548-1.878a1.5 1.5 0 0 1 1.404 0L16.25 4.75A1.194 1.194 0 0 1 15.691 7H8.309a1.194 1.194 0 0 1-.559-2.25");
}

.eykzzpblx {
  d: path("M7 7h10a1.5 1.5 0 0 1 1.5 1.5V10a1.5 1.5 0 0 1-1.5 1.5H7A1.5 1.5 0 0 1 5.5 10V8.5A1.5 1.5 0 0 1 7 7m-1 4.5h12a1.5 1.5 0 0 1 1.5 1.5v1.5A1.5 1.5 0 0 1 18 16H6a1.5 1.5 0 0 1-1.5-1.5V13A1.5 1.5 0 0 1 6 11.5M7 16h10a1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5H7A1.5 1.5 0 0 1 5.5 19v-1.5A1.5 1.5 0 0 1 7 16m-4 4.5h18m-10.25-2.25h2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
