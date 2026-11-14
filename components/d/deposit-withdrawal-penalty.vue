<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xys9lvbka"/><path class="rhr3mnkku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-withdrawal-penalty" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rhr3mnkku {
  d: path("M4.5 10.5h-2v3h2m3.25-2.75h.01M10.5 8.5h3m4.5 6v4m0 2.75h.01");
}

.xys9lvbka {
  d: path("M15.385 19.5H14v-1.75c-.75.25-1.25.25-2 .25s-1.25 0-2-.25v1.75H7.5V17C5.25 16 4 14.25 4 12c0-3.5 3.5-6 8-6s8 2.5 8 6q0 .28-.025.548");
}

</style>
