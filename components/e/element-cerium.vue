<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="tov3f6n6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:element-cerium" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.tov3f6n6v {
  d: path("M17.75 8.75a6.5 3.5-30 0 1-11.5 6.5a6.5 3.5-30 0 1 11.5-6.5ZM12 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
