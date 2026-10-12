<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvw0zzdwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gutter-drain-sharp" /></template>
<style>
.qvw0zzdwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5m-18.5 2.5h18.5V8.5H2.75zm4.25 0V8.5m5-3.25V8.5m4 0h3v11.75h-6.5v-3H16Zm-7.5 7l1.6 2v.95a1.6 1.6 0 0 1-3.2 0v-.95z");
}

</style>
