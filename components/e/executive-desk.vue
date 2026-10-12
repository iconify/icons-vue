<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="cv_7_4bvk"/><path class="th_wd4boo"/><rect class="v-datx-di"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:executive-desk" /></template>
<style>
.cv_7_4bvk {
  cx: 12px;
  cy: 6.25px;
  r: 3.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.th_wd4boo {
  d: path("M7.25 16.25h9.5a.75.75 0 0 0 .75-.75c0-2.03-2.53-3.5-5.5-3.5s-5.5 1.47-5.5 3.5a.75.75 0 0 0 .75.75");
}

.v-datx-di {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 16.25px;
  rx: 1.5px;
}

</style>
