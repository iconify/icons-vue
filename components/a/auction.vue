<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpc10l00a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:auction" /></template>
<style>
.kpc10l00a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.72 5.5l1.78-1.78q.88-.88 1.76 0l6.02 6.02q.88.88 0 1.76l-1.78 1.78q-.88.88-1.76 0L8.72 7.26q-.88-.88 0-1.76m2.78 5l-7.25 7.25m8.5 3h8.5");
}

</style>
