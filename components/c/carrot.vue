<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9f3tcjnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:carrot" /></template>
<style>
.z9f3tcjnn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.2 17.66l7.33-11.13a3.5 3.5 0 0 1 4.94 4.94L6.34 18.8a.81.81 0 0 1-1.14-1.14M18.25 5.75l2.5-2.5m-4.75 2l.75-2.5m2 5.25l2.5-.75m-11 5l1.5 1.5");
}

</style>
