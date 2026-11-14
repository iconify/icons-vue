<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxyyo1b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fuel-farm" /></template>
<style>
.uxyyo1b8s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.5v-8c0-2.5 4.75-2.5 4.75 0v8m2.5 0v-11c0-2.5 4.5-2.5 4.5 0v11m2.5 0v-8c0-2.5 4.75-2.5 4.75 0v8M2 18.5h20m-14.75-3h2.5m4.5 0h2.5");
}

</style>
