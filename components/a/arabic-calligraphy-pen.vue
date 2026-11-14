<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrw5xcc8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arabic-calligraphy-pen" /></template>
<style>
.xrw5xcc8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.561 4.561l.878.878a1.5 1.5 0 0 1 0 2.122l-8.704 8.704a1.5 1.5 0 0 1-.548.349l-2.56.931A1.114 1.114 0 0 1 6.25 16l1.141-2.282a1.5 1.5 0 0 1 .281-.39l8.767-8.767a1.5 1.5 0 0 1 2.122 0M15.5 16s2.25 2.5 2.25 3.75a2.25 2.25 0 0 1-4.5 0c0-1.25 2.25-3.75 2.25-3.75");
}

</style>
