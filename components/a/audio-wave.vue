<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvmtkac6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:audio-wave" /></template>
<style>
.wvmtkac6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 10.5v3m2.75-6v9m5.5-8v7M17.5 7v10m2.75-7v4m-11-9.25v14.5m5.5-15.5v16.5");
}

</style>
