<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf5oictxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:magnetic-gripper" /></template>
<style>
.bf5oictxs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13.5v-4a7 7 0 0 1 14 0v4h-4v-4a3 3 0 0 0-6 0v4ZM3.5 17h17v3h-17ZM5 11.5h4m6 0h4");
}

</style>
