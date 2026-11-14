<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl_odub_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:artist-profile" /></template>
<style>
.wl_odub_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 5.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M7 13c0-1.75 2.25-2.25 5-2.25s5 .5 5 2.25M5.625 15.75h12.75A2.625 2.625 0 0 1 21 18.375v.5a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-.5a2.625 2.625 0 0 1 2.625-2.625m.875 3h4m3 0h4");
}

</style>
