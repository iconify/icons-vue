<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8qxpub2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hat" /></template>
<style>
.p8qxpub2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 15.5V9.75a3.5 3.5 0 0 1 3.5-3.5h3.5a3.5 3.5 0 0 1 3.5 3.5v5.75h2.25a1.75 1.75 0 0 1 0 3.5h-15a1.75 1.75 0 0 1 0-3.5Zm0-2.75h10.5");
}

</style>
