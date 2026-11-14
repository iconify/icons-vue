<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylds_wbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floorboards" /></template>
<style>
.ylds_wbdx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.207 4h9.586a1.5 1.5 0 0 1 1.465 1.179l2.844 13A1.5 1.5 0 0 1 19.636 20H4.364a1.5 1.5 0 0 1-1.466-1.821l2.844-13A1.5 1.5 0 0 1 7.207 4M10 4L8.75 20M14 4l1.25 16M4 13h5.25m.5-5h4.5m.5 7h5.75");
}

</style>
