<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjl7wfbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:handout" /></template>
<style>
.hjl7wfbus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5H12A3.5 3.5 0 0 1 15.5 6v12a3.5 3.5 0 0 1-3.5 3.5H6.5A3.5 3.5 0 0 1 3 18V6a3.5 3.5 0 0 1 3.5-3.5m-.5 4h6.5m-6.5 4h6.5M6 14h3.5M6 17.5h5m1.5-3.5h9m-3-3l3 3l-3 3");
}

</style>
