<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6iz94bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:awning" /></template>
<style>
.d6iz94bsn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 9l1.5-5h15L21 9Zm0 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M5 12v8.5M19 12v8.5");
}

</style>
