<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvrwmpfgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:collision-warning-sharp" /></template>
<style>
.bvrwmpfgu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 16.25v-3.5l.97-.24l.06-.02l.97-.24l.35-.94l.8-2.12l.35-.94h5l.55.83l1.4 2.09l.55.83l.96.29l.58.17l.96.29v4.5H2.75zm2-4h9m-8.75 5V19h3.5v-1.75m2.25 0V19h3.5v-1.75m5-7.5l2-1.75m-2 5.5h2m-2 3.75l2 1.75");
}

</style>
