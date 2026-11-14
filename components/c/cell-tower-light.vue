<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf0yajb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cell-tower-light" /></template>
<style>
.xf0yajb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 21.5l4-13l4 13M10 15h4M12 5h.01M8.5 2.5a3.5 3.5 0 0 0 0 5m7-5a3.5 3.5 0 0 1 0 5");
}

</style>
