<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4tgnwbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:independence-fireworks" /></template>
<style>
.k4tgnwbqm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.75V2.5m2 5l3-3m-2.25 5H19m-5 2l3 3m-7-3l-3 3m2.25-5H5m5-2l-3-3m1.5 17c2.5-2 3.5-4 3.5-7.5m0-4.5h.01");
}

</style>
