<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x34oo_ogw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:llm-judge" /></template>
<style>
.x34oo_ogw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5v17m-3.5 0h7m-10-14h13M2.5 12l3-5.5l3 5.5a3 3 0 0 1-6 0m13 0l3-5.5l3 5.5m-6 0h6v3.5A1.5 1.5 0 0 1 20 17h-2.25l-2.25 1.5Z");
}

</style>
