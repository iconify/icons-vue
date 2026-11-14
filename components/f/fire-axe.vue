<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6xfqjdcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-axe" /></template>
<style>
.h6xfqjdcm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.75 5.25l3.136 1.689a1.5 1.5 0 0 0 .237.102l2.127.709a1.466 1.466 0 0 1 .573 2.427l-2.646 2.646a1.466 1.466 0 0 1-2.427-.573l-.709-2.127a1.5 1.5 0 0 0-.102-.237L12.25 6.75a1.107 1.107 0 0 1 1.5-1.5M3 21l11-11");
}

</style>
