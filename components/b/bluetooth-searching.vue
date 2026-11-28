<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na8pc_ksa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bluetooth-searching" /></template>
<style>
.na8pc_ksa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 7L17 17L12 22L12 2L17 7L7 17M21.1652 8C21.7158 9.2617 22 10.6234 22 12C22 13.3766 21.7158 14.7383 21.1652 16M2.8348 8C2.2842 9.2617 2 10.6234 2 12C2 13.3766 2.2842 14.7383 2.8348 16");
}

</style>
