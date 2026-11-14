<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2qbu2bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:interrobang" /></template>
<style>
.m2qbu2bvi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8.5C7.5 5.75 9.5 4 12 4s4.5 1.75 4.5 4c0 3.25-4.5 3.75-4.5 6.5M12 4v10.5m0 4.5h.01");
}

</style>
