<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qessq5byk"/><path class="og1t_xayx"/><path class="vyobxn3tp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cat-bed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.og1t_xayx {
  d: path("M2.5 10.5v3a9.5 5 0 0 0 19 0v-3");
}

.qessq5byk {
  d: path("M2.5 10.5a9.5 5 0 1 0 19 0a9.5 5 0 1 0-19 0");
}

.vyobxn3tp {
  d: path("M7 10a5 1.75 0 1 0 10 0a5 1.75 0 1 0-10 0");
}

</style>
