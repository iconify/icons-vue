<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfevn671v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gateway-arch" /></template>
<style>
.wfevn671v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 18.25C3.75 9 7.5 2.75 12 2.75s8.25 6.25 8.75 15.5H17.5C17 10.5 14.75 6 12 6s-5 4.5-5.5 12.25Zm-.5 3h18.5");
}

</style>
