<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyufzibvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:case-pack" /></template>
<style>
.fyufzibvc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11h19v9.5h-19ZM4 11V5a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v6m2 0V5a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v6m2 0V5a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v6");
}

</style>
