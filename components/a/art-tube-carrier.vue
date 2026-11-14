<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te5j3_waq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:art-tube-carrier" /></template>
<style>
.te5j3_waq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 9h-13a2.5 4.5 0 0 0 0 9h13a2.5 4.5 0 0 0 0-9a2.5 4.5 0 0 0 0 9m-11-9q4.5-7 9 0");
}

</style>
