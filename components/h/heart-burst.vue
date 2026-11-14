<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phhkolr9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-burst" /></template>
<style>
.phhkolr9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 20c-4.5-3-5.5-5.25-5.5-7.25s1.4-3.5 3.25-3.5c1 0 1.75.5 2.25 1.25c.5-.75 1.25-1.25 2.25-1.25c1.85 0 3.25 1.5 3.25 3.5S16.5 17 12 20m0-17v3.5M4.5 6l1.75 1.75M19.5 6l-1.75 1.75M2.5 13H4m17.5 0H20");
}

</style>
