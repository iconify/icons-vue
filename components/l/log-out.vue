<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqffa1gmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:log-out" /></template>
<style>
.fqffa1gmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 3.75h-3a2.5 2.5 0 0 0-2.5 2.5v11.5a2.5 2.5 0 0 0 2.5 2.5h3m11-8.25H9.75m6.75-3.75L20.25 12l-3.75 3.75");
}

</style>
