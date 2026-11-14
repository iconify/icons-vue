<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd49vpb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:avalanche-probe" /></template>
<style>
.dd49vpb5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5c1-4 5-6.5 9.5-6.5s8.5 2.5 9.5 6.5Zm15-17L13.75 14m1.5-11.25l4.5 1.5");
}

</style>
