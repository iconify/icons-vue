<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cu-7bb6je"/><path class="a82ngpu0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cancer-centre" /></template>
<style>
.a82ngpu0j {
  d: path("M9 18.75L13.75 12a2.5 2.5 0 1 0-3.5 0L15 18.75");
}

.cu-7bb6je {
  d: path("M2.5 21.5V10h4V4.5h11V10h4v11.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
