<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp18npb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:church-door-arched" /></template>
<style>
.pp18npb9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21.5V11A10.5 10.5 0 0 1 12 2.5a10.5 10.5 0 0 1 7.5 8.5v10.5Zm7.5-19v19M9.25 14h.01m5.49 0h.01");
}

</style>
