<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fuiyxrxlt"/><path class="a2g_b7bjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:balloon-number" /></template>
<style>
.a2g_b7bjd {
  d: path("M12 16.75c0 1.75 1.25 2.75.5 4.75m-2-14.25l2-1.5v5.75");
}

.fuiyxrxlt {
  d: path("M12 15c-3.25 0-6-3-6-6.5c0-3.25 2.75-5.75 6-5.75s6 2.5 6 5.75c0 3.5-2.75 6.5-6 6.5m.625.875za.553.553 0 0 1-.45.875h-.35a.553.553 0 0 1-.45-.875a.768.768 0 0 1 1.25 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
