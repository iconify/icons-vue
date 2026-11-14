<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx_ekb3ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hydrogen-pipeline" /></template>
<style>
.zx_ekb3ob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14H15V9.5h4.5V16a2.5 2.5 0 0 1-2.5 2.5H2.5Zm14.75-9.5v5m-3.75-5H21");
}

</style>
