<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkumuzbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baggage-weight-limit" /></template>
<style>
.fkumuzbsr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9h14l2 11H3Zm4.5-3.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m2.5 9l2-2");
}

</style>
