<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjgbvrbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boxing-shorts" /></template>
<style>
.mjgbvrbib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 4.5h12.5A1.75 1.75 0 0 1 20 6.25v.5a1.75 1.75 0 0 1-1.75 1.75H5.75A1.75 1.75 0 0 1 4 6.75v-.5A1.75 1.75 0 0 1 5.75 4.5m-.25 4L3.5 20h7l1.5-5.5l1.5 5.5h7l-2-11.5");
}

</style>
