<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hphqxdbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bold-text" /></template>
<style>
.hphqxdbbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.75h5.75a4 4 0 0 1 0 8a4 4 0 0 1 0 8H6.75Zm3.25 4h2.25m-2.25 8h2.5m-5.75 6.5h10.5");
}

</style>
