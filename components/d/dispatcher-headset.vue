<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="potddqhfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dispatcher-headset" /></template>
<style>
.potddqhfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12V9.5a7 7 0 0 1 14 0V12M3 12h4v7H3Zm14 0h4v7h-4ZM5 19q0 2.5 3.5 2.5h3");
}

</style>
