<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="vh25ytu5a"/><circle class="dhj1gvblj"/><path class="bmhulzbig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:forceps-med" /></template>
<style>
.bmhulzbig {
  d: path("M8.75 16.6L12 9.5l3.25 7.1M12 9.5V2.75M10.75 15h2.5");
}

.dhj1gvblj {
  cx: 16.5px;
  cy: 18.75px;
  r: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vh25ytu5a {
  cx: 7.5px;
  cy: 18.75px;
  r: 2.5px;
}

</style>
