<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agk3azb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:corset" /></template>
<style>
.agk3azb-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 6c3 4.5 3 9.5-.5 15h13C15 15.5 15 10.5 18 6Q12 9.75 6 6m0 0l1-3.5M18 6l-1-3.5m-5 7.75v8.25");
}

</style>
