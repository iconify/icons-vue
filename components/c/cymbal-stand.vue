<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vog_jwq1a"/><path class="kp9hkxojh"/><path class="t4mssrbdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cymbal-stand" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kp9hkxojh {
  d: path("M9 21.5V10l4-2.75");
}

.t4mssrbdw {
  d: path("m3.5 21.5l5.5-5l5.5 5");
}

.vog_jwq1a {
  d: path("M6.5 5.5a7.5 2 0 1 0 15 0a7.5 2 0 1 0-15 0");
}

</style>
