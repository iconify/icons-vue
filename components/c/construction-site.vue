<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rgasv6box"/><path class="pq_jgetpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:construction-site" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pq_jgetpq {
  d: path("M17 6v7.5a2 2 0 1 1-2 2");
}

.rgasv6box {
  d: path("M2.5 6h19l-14-3.5v19m-3.5 0h7");
}

</style>
