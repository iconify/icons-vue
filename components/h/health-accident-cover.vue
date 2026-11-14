<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7azp19pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:health-accident-cover" /></template>
<style>
.j7azp19pn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.575 14.475l9.9-9.9a3.5 3.5 0 0 1 4.95 0a3.5 3.5 0 0 1 0 4.95l-9.9 9.9a3.5 3.5 0 0 1-4.95 0a3.5 3.5 0 0 1 0-4.95m3.182-3.182l4.95 4.95m-1.414-8.486l4.95 4.95");
}

</style>
