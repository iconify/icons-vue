<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7x7liozs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leave-now" /></template>
<style>
.x7x7liozs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm5 5v9m-2.5 0h5m4-3h6M19 16l2.5 2.5L19 21");
}

</style>
