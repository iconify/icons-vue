<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuyddya0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:break-room" /></template>
<style>
.tuyddya0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11V9a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v2M3 11h18v6H3Zm2.5 6v2.5m13-2.5v2.5");
}

</style>
