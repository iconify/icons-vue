<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="frrxzxbga"/><path class="het3hgz1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cup-saucer" /></template>
<style>
.frrxzxbga {
  d: path("M4.25 5h11.5v4.75a5.75 5.75 0 0 1-11.5 0Z");
}

.het3hgz1p {
  d: path("M15.75 6.75h1.75a2.5 2.5 0 0 1 0 5h-2.25M2.75 18.5h18.5c-.75 1.75-2.25 2.75-4 2.75H6.75c-1.75 0-3.25-1-4-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
