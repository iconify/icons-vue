<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9hwqhtnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hanukkah-menorah" /></template>
<style>
.a9hwqhtnp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8a7.5 7.5 0 0 0 15 0M8 8a4 4 0 0 0 8 0m-4 0v12.5m-4.5 0h9M4.5 5h.01M8 5h.01M12 5h.01M16 5h.01m3.49 0h.01");
}

</style>
