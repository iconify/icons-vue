<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dl0khne4j"/><path class="qkfw_hbdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:birthday-gift" /></template>
<style>
.dl0khne4j {
  d: path("M5.625 11h6.25a2.625 2.625 0 0 1 2.625 2.625v4.75A2.625 2.625 0 0 1 11.875 21h-6.25A2.625 2.625 0 0 1 3 18.375v-4.75A2.625 2.625 0 0 1 5.625 11m3.125 0v10m0-10C7.5 8.5 5 7.5 5 9.25c0 1 1.75 1.75 3.75 1.75m0 0C10 8.5 12.5 7.5 12.5 9.25c0 1-1.75 1.75-3.75 1.75m6.75-4.5a2.75 3.5 0 1 0 5.5 0a2.75 3.5 0 1 0-5.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qkfw_hbdn {
  d: path("M18.25 10v2l-.75 2");
}

</style>
