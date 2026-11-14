<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsqb5dtgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:led-wall" /></template>
<style>
.fsqb5dtgk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19v12.5h-19ZM6 16.5v4m12-4v4M7 8h.01M12 8h.01M17 8h.01M7 12.5h.01m4.99 0h.01m4.99 0h.01");
}

</style>
