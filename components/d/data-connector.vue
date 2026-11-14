<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tijqe008i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-connector" /></template>
<style>
.tijqe008i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 9h5a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-5a3 3 0 0 1-3-3a3 3 0 0 1 3-3m0-5.5V9m5-5.5V9M12 15v5.5");
}

</style>
