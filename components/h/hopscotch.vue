<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1vcq3b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hopscotch" /></template>
<style>
.m1vcq3b7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 2.5h4.5v3.75h2.25V10h-2.25v3.75h2.25v3.75h-2.25v3.75h-4.5V17.5H7.5v-3.75h2.25V10H7.5V6.25h2.25Zm0 3.75h4.5M9.75 10h4.5m-4.5 3.75h4.5m-4.5 3.75h4.5M12 6.25V10m0 3.75v3.75");
}

</style>
