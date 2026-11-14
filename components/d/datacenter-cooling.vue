<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7kkb0bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:datacenter-cooling" /></template>
<style>
.g7kkb0bxf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.8 19H3.5V2.5h15v10.2M3.5 8h15m-15 5.5h10.7m.7 0h.5M7 5.25h.01M7 10.75h.01M7 16.25h.01m11.24-.75v6M15.5 17l5.5 3m-5.5 0l5.5-3");
}

</style>
