<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0mekdkgc"/><path class="f7q_gopah"/><circle class="poj5y7bey"/><path class="ofibmb_yq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:database-query" /></template>
<style>
.f7q_gopah {
  d: path("M3.25 6c0 1.8 3.02 3.25 6.75 3.25S16.75 7.8 16.75 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ofibmb_yq {
  d: path("m18.9 16.9l2.35 2.35");
}

.poj5y7bey {
  cx: 16.75px;
  cy: 14.75px;
  r: 3px;
}

.r0mekdkgc {
  d: path("M3.25 6c0-1.8 3.02-3.25 6.75-3.25S16.75 4.2 16.75 6v11c0 1.8-3.02 3.25-6.75 3.25S3.25 18.8 3.25 17Z");
}

</style>
