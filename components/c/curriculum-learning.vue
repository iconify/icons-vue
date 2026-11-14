<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dc_d9qbju"/><path class="y_lgkdbvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:curriculum-learning" /></template>
<style>
.dc_d9qbju {
  d: path("M2.5 20.5h19v-9H17v3H9.5v3h-7Zm13-10.5V5.5A1.5 1.5 0 0 1 17 4h4.5v7.5H17a1.5 1.5 0 0 1-1.5-1.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_lgkdbvx {
  d: path("M15.5 10A1.5 1.5 0 0 1 17 8.5h4.5");
}

</style>
