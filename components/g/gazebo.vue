<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib7m0vcps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gazebo" /></template>
<style>
.ib7m0vcps {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 9.75C3.25 6.25 7.25 3 12 3s8.75 3.25 8.75 6.75Zm1.75 0v11.5m14-11.5v11.5M9.5 9.75v11.5m5-11.5v11.5m-11.75 0h18.5M5 15.5h14");
}

</style>
