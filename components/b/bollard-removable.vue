<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og724-byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bollard-removable" /></template>
<style>
.og724-byi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 15V6.5a2.5 2.5 0 0 1 5 0V15Zm-3.5 4h3v2.5h6V19h10M17 15.5V5m-2.75 2.75L17 5l2.75 2.75");
}

</style>
