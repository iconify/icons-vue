<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hxvumc12l"/><path class="c6v292b8v"/><path class="iway7y6kf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clubhouse" /></template>
<style>
.c6v292b8v {
  d: path("M4 12.5v9h16v-9m-8-5v-5m1.423.474l.827.276a.791.791 0 0 1 0 1.5l-.827.276A1.08 1.08 0 0 1 12 4a1.08 1.08 0 0 1 1.423-1.026");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxvumc12l {
  d: path("m7.25 10l4.051-2.132a1.5 1.5 0 0 1 1.398 0L16.75 10a1.326 1.326 0 0 1-.618 2.5H7.868A1.326 1.326 0 0 1 7.25 10");
}

.iway7y6kf {
  d: path("M10 21.5V17h4v4.5M6.5 16H8m8 0h1.5");
}

</style>
