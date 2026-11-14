<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="og_tf12ef"/><path class="tp7u0ubgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cinema-hall" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.og_tf12ef {
  d: path("M5.125 3.5h13.75A2.625 2.625 0 0 1 21.5 6.125v1.25A2.625 2.625 0 0 1 18.875 10H5.125A2.625 2.625 0 0 1 2.5 7.375v-1.25A2.625 2.625 0 0 1 5.125 3.5M4.5 10v10.5h15V10M7 6.75h.01m4.99 0h.01m4.99 0h.01");
}

.tp7u0ubgd {
  d: path("M9.5 20.5v-7h5v7m-2.5-7v7");
}

</style>
