<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vkunq556k"/><path class="m_l7hk9ss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-transfer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_l7hk9ss {
  d: path("M14.75 8.5L18 9l.5-3.25");
}

.vkunq556k {
  d: path("M5.125 12h1.75A2.625 2.625 0 0 1 9.5 14.625v1.75A2.625 2.625 0 0 1 6.875 19h-1.75A2.625 2.625 0 0 1 2.5 16.375v-1.75A2.625 2.625 0 0 1 5.125 12m12 0h1.75a2.625 2.625 0 0 1 2.625 2.625v1.75A2.625 2.625 0 0 1 18.875 19h-1.75a2.625 2.625 0 0 1-2.625-2.625v-1.75A2.625 2.625 0 0 1 17.125 12M6 9q6-8 12 0");
}

</style>
