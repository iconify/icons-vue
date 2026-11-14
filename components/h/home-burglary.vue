<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h5-qq5bsj"/><path class="rx_4h6baq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-burglary" /></template>
<style>
.h5-qq5bsj {
  d: path("M15.244 20.5H3.5v-10L12 3.25l8.5 7.25v1.156");
}

.rx_4h6baq {
  d: path("M9.5 20.5V14H13v6.5M9.5 14l-3 1.5v5m11.5-6V18m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
