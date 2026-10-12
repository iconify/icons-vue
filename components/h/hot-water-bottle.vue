<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3dlsntbj"/><path class="g1jok_bdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hot-water-bottle" /></template>
<style>
.g1jok_bdu {
  d: path("M7.5 13.75q2.25-1.5 4.5 0c2.25 1.5 3 1 4.5 0m-9 3.5q2.25-1.5 4.5 0c2.25 1.5 3 1 4.5 0M8.75 5.5V4.25A1.25 1.25 0 0 1 10 3h4a1.25 1.25 0 0 1 1.25 1.25V5.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r3dlsntbj {
  d: path("M9.25 5.5h5.5v1.75c0 .5.25.75.75.85l2.75.9c.75.25 1.25 1 1.25 1.75v6.5a4 4 0 0 1-4 4h-7a4 4 0 0 1-4-4v-6.5C4.5 10 5 9.25 5.75 9l2.75-.9c.5-.1.75-.35.75-.85Z");
}

</style>
