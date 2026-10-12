<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpppw_bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:central-bank" /></template>
<style>
.lpppw_bna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8a5 5 0 0 1 10 0Zm-3.75 3h17.5m-15 3v4m4-4v4m4.5-4v4m4-4v4m-15 2.75h17.5");
}

</style>
