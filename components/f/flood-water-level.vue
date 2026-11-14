<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o28jpls6t"/><path class="hpmardb4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flood-water-level" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hpmardb4h {
  d: path("M2.5 14.5c1.58-1.25 3.17-1.25 4.75 0s3.17 1.25 4.75 0s3.17-1.25 4.75 0s3.17 1.25 4.75 0m-19 4c1.58-1.25 3.17-1.25 4.75 0s3.17 1.25 4.75 0s3.17-1.25 4.75 0s3.17 1.25 4.75 0");
}

.o28jpls6t {
  d: path("M15.25 2.5h1.5a1.75 1.75 0 0 1 1.75 1.75v15.5a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75V4.25a1.75 1.75 0 0 1 1.75-1.75M13.5 6H16m-2.5 3.5H16");
}

</style>
