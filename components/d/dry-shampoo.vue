<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l69gz0bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dry-shampoo" /></template>
<style>
.l69gz0bsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9h9.5v12.5H5Zm2 0l1.5-3H11l1.5 3M9.75 6V3.5h2.75m3.25 0h.01M19 3h.01M18 6.25h.01");
}

</style>
