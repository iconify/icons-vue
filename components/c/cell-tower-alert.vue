<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tioipcsdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cell-tower-alert" /></template>
<style>
.tioipcsdc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 21.5l5.5-14l4.921 12.526M7.75 14.5h5.5L5 21.5m2.75-7l7.473 6.34M10.5 4.75h.01M8.555 6.695a2.75 2.75 0 0 1 0-3.89m3.89 0a2.75 2.75 0 0 1 0 3.89M18 14.5V18m0 3h.01");
}

</style>
