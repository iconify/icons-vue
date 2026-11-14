<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rnke8bc4z"/><path class="zz3ijbcpf"/><path class="x29m_-b8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:appendix" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rnke8bc4z {
  d: path("M8 2.5h9.5A2.5 2.5 0 0 1 20 5v13.5");
}

.x29m_-b8m {
  d: path("M10.5 5.5v7l1.75-1.5L14 12.5v-7M6.5 17h7");
}

.zz3ijbcpf {
  d: path("M7 5.5h6.5A3.5 3.5 0 0 1 17 9v9a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18V9A3.5 3.5 0 0 1 7 5.5");
}

</style>
