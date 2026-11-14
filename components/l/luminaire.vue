<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikx5lvkcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:luminaire" /></template>
<style>
.ikx5lvkcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v5M4.5 15c0-4.5 3.25-7.5 7.5-7.5s7.5 3 7.5 7.5Zm5 0a2.5 2.5 0 0 0 5 0M12 20.25v1.5");
}

</style>
