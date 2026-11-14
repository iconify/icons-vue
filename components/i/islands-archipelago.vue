<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gflxs44jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:islands-archipelago" /></template>
<style>
.gflxs44jk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h1c1-9 6.5-9 7.5 0h1.5c.75-5.5 3.75-5.5 4.5 0h.5c.5-2.75 3-2.75 3.5 0h.5M4 16q2.5-1.5 5 0t5 0t5 0M7 20q2.5-1.5 5 0t5 0");
}

</style>
