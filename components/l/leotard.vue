<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w1zjl4b3s"/><path class="n5v89obeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leotard" /></template>
<style>
.n5v89obeg {
  d: path("M8.5 6.5q3.5 4.5 7 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w1zjl4b3s {
  d: path("M8.5 2.5v4c0 1.5-3 2.5-3 5v2l5 8h3l5-8v-2c0-2.5-3-3.5-3-5v-4");
}

</style>
