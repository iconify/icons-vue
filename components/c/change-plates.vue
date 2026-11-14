<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az099qpqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:change-plates" /></template>
<style>
.az099qpqp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 4za1.75 1.75 0 0 1 1.75 1.75v12.5A1.75 1.75 0 0 1 8.75 20A1.75 1.75 0 0 1 7 18.25V5.75A1.75 1.75 0 0 1 8.75 4m6 3za1.5 1.5 0 0 1 1.5 1.5v7a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-7a1.5 1.5 0 0 1 1.5-1.5M2.5 12H7m3.5 0h2.75m3 0h5.25");
}

</style>
