<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eidihvb2m"/><path class="gu2275b3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:linter" /></template>
<style>
.eidihvb2m {
  d: path("M3 10a7 7 0 1 0 14 0a7 7 0 1 0-14 0m12 5l5.5 5.5");
}

.gu2275b3a {
  d: path("m7 10l2.25 2.25L13 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
