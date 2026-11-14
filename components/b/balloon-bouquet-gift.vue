<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hc4mqjbqx"/><path class="u70g162xj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:balloon-bouquet-gift" /></template>
<style>
.hc4mqjbqx {
  d: path("M9.125 14.5h5.75a2.625 2.625 0 0 1 2.625 2.625v1.75a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 6.5 18.875v-1.75A2.625 2.625 0 0 1 9.125 14.5m-5.375-8a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m6-2a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m6 2a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u70g162xj {
  d: path("m6 8.75l6 5.75l6-5.75m-6-2V21.5");
}

</style>
