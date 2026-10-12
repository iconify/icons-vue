<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jaknr8b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ankh-symbol" /></template>
<style>
.jaknr8b8v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11.75c-2.5-1.5-4-3.5-4-5.5a4 3.5 0 0 1 8 0c0 2-1.5 4-4 5.5m-8.25.5h16.5m-8.9 0h1.3q.6 0 .67.6l.86 7.8q.07.6-.53.6h-3.3q-.6 0-.53-.6l.86-7.8q.07-.6.67-.6");
}

</style>
