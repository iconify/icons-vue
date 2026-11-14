<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ru69vacof"/><path class="g_q03qb5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:city-skyline-night" /></template>
<style>
.g_q03qb5f {
  d: path("M20.5 14A5 5 0 1 1 16 6.5a4 4 0 0 0 4.5 7.5Z");
}

.ru69vacof {
  d: path("M3 21v-9h5v9m0 0V7h6v14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
