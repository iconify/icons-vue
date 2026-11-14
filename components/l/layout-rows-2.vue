<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnbtsbcip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:layout-rows-2" /></template>
<style>
.mnbtsbcip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.75h15.5A1.75 1.75 0 0 1 21.5 4.5v4.25a1.75 1.75 0 0 1-1.75 1.75H4.25A1.75 1.75 0 0 1 2.5 8.75V4.5a1.75 1.75 0 0 1 1.75-1.75m0 10.5h15.5A1.75 1.75 0 0 1 21.5 15v4.25A1.75 1.75 0 0 1 19.75 21H4.25a1.75 1.75 0 0 1-1.75-1.75V15a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
