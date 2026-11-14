<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pu9gtsbzf"/><path class="l_x7ebbqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gravitational-wave" /></template>
<style>
.l_x7ebbqs {
  d: path("M2.5 15.5q1.5-1.5 3 0q1.75 2.5 3.5 0q2-3.5 4 0q2 4.5 4 0q2.25-5.5 4.5 0");
}

.pu9gtsbzf {
  d: path("M2.5 8.5q1.5-1.5 3 0Q7.25 11 9 8.5q2-3.5 4 0q2 4.5 4 0q2.25-5.5 4.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
