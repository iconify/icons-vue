<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iej5m7q0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:decking-boards" /></template>
<style>
.iej5m7q0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.093 5h7.814a1.5 1.5 0 0 1 1.428 1.041l3.535 11A1.5 1.5 0 0 1 19.442 19H4.558a1.5 1.5 0 0 1-1.428-1.959l3.535-11A1.5 1.5 0 0 1 8.093 5m2.157 0l-1.5 14m5-14l1.5 14m-10.5-7H9.5m4.75-3h4");
}

</style>
