<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l415t1btw"/><path class="a42iin_iw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:benefit-company-badge" /></template>
<style>
.a42iin_iw {
  d: path("m8.25 12.25l2.5 2.5l5-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l415t1btw {
  d: path("m20.01 13.719l-1.418 1.637a2.6 2.6 0 0 0-.507.889l-.595 1.784a2.625 2.625 0 0 1-3.031 1.739l-1.918-.404a2.6 2.6 0 0 0-1.082 0l-1.918.404a2.625 2.625 0 0 1-3.031-1.739l-.595-1.784a2.6 2.6 0 0 0-.507-.889L3.99 13.719a2.625 2.625 0 0 1 0-3.438l1.418-1.637a2.6 2.6 0 0 0 .507-.889l.595-1.784a2.625 2.625 0 0 1 3.031-1.739l1.918.404a2.6 2.6 0 0 0 1.082 0l1.918-.404a2.625 2.625 0 0 1 3.031 1.739l.595 1.784a2.6 2.6 0 0 0 .507.889l1.418 1.637a2.625 2.625 0 0 1 0 3.438");
}

</style>
