<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5dlu8f0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-edit" /></template>
<style>
.v5dlu8f0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2 20.5H3.5V5h17v5.8M8 3v4m8-4v4M3.5 10h17M8 3v4m8-4v4M3.5 10h17M15 21l.5-2.25l4.5-4.5L21.75 16l-4.5 4.5Z");
}

</style>
