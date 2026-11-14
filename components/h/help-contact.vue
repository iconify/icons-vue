<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a85j3db8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:help-contact" /></template>
<style>
.a85j3db8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 11.75v-1.5a7.25 7.25 0 0 1 14.5 0v1.5m-16.75 0H7v6.5H2.5Zm14.5 0h4.5v6.5H17Zm2.25 6.5c0 2.25-1.75 2.75-6.75 2.75");
}

</style>
