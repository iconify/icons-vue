<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecugc4b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:iron-clothes-sharp" /></template>
<style>
.ecugc4b5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25h18.5v-7h-12c-3.25 0-5.5 3-6.5 7Zm6.75-7l1-3.25H19v3.25M9 3c-.9 1.15.9 2.1 0 3.25M13 3c-.9 1.15.9 2.1 0 3.25M17 3c-.9 1.15.9 2.1 0 3.25");
}

</style>
