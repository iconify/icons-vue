<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv4b-gb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:escalation-tier-3" /></template>
<style>
.zv4b-gb7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 9.25l7.5-5.5l7.5 5.5m-15 5.5l7.5-5.5l7.5 5.5m-15 5.5l7.5-5.5l7.5 5.5");
}

</style>
