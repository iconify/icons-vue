<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gcifhwhlz"/><path class="n1clzq4fw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cloud-iam" /></template>
<style>
.gcifhwhlz {
  d: path("M6 19h11a4 4 0 0 0 0-8a6 6 0 0 0-11.75.75A3.75 3.75 0 0 0 6 19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n1clzq4fw {
  d: path("M9.5 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1.75 8c0-2 1.75-3.5 3.75-3.5s3.75 1.5 3.75 3.5");
}

</style>
