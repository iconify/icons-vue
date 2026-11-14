<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g8__4h8kl"/><path class="bzbxzac9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garage" /></template>
<style>
.bzbxzac9p {
  d: path("M8.5 12.5h7A1.5 1.5 0 0 1 17 14v5a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 19v-5a1.5 1.5 0 0 1 1.5-1.5m-1.5 3h10M7 18h10");
}

.g8__4h8kl {
  d: path("m3.676 10.475l7.25-5.639a1.75 1.75 0 0 1 2.148 0l7.25 5.639A1.75 1.75 0 0 1 21 11.856v6.894a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 18.75v-6.894a1.75 1.75 0 0 1 .676-1.381");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
