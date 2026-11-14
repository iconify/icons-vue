<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="o7gb6m9ml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arch-pointed" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.o7gb6m9ml {
  d: path("M8.5 21v-8A7 7 0 0 1 12 7a7 7 0 0 1 3.5 6v8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
