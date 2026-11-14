<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o8-vzsboq"/><path class="dou4n5biz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lab-mouse" /></template>
<style>
.dou4n5biz {
  d: path("m6.5 6.5l3 2.5l-3 2.5m5 0h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o8-vzsboq {
  d: path("M6.875 2.5h10.25A4.375 4.375 0 0 1 21.5 6.875v4.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 11.125v-4.25A4.375 4.375 0 0 1 6.875 2.5M6 18.5h12a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H6A1.5 1.5 0 0 1 4.5 20A1.5 1.5 0 0 1 6 18.5");
}

</style>
