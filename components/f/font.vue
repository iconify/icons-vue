<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_q6c3bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:font" /></template>
<style>
.z_q6c3bmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 20l5-15.5l5 15.5m-8.25-5h6.5m3.75 1.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0m6-3.25V20");
}

</style>
