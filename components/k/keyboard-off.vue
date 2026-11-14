<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un3fgl1fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keyboard-off" /></template>
<style>
.un3fgl1fv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.1 18H2V6h.1m7.8 0H22v12h-.1M14 9.75h.01m3.99 0h.01M6 14.25h.01m2.49 0h1.8M3.5 3.5l17 17");
}

</style>
