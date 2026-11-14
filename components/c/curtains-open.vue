<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8bxno7qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:curtains-open" /></template>
<style>
.k8bxno7qf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19M4 3.5V21h4q-2.5-6-1.5-9q3-5 3.5-8.5m10 0V21h-4q2.5-6 1.5-9q-3-5-3.5-8.5");
}

</style>
