<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cno08ab0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaderboard-ai" /></template>
<style>
.cno08ab0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5V16H9v-3.25h6V18h5.5v3.5ZM9 16v5.5m6-3.5v3.5M12 3l1.029 2.334l2.537.257l-1.902 1.7l.54 2.493L12 8.5L9.796 9.784l.54-2.493l-1.902-1.7l2.537-.257Z");
}

</style>
