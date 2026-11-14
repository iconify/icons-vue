<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p7-8m00vw"/><path class="tsa8i7btx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-filter" /></template>
<style>
.p7-8m00vw {
  d: path("M12.125 15.697L9 17.5l-6.5-3.75v-7.5L9 2.5l6.5 3.75v3.996");
}

.tsa8i7btx {
  d: path("M2.5 6.25L9 10l6.5-3.75M9 11.8v5.7m4.5-4.5h8l-3 3.75v4.75l-2-1v-3.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
