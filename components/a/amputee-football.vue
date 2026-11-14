<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyr9z5bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:amputee-football" /></template>
<style>
.eyr9z5bdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5a9 9 0 0 1 11-11a9 9 0 0 1-11 11m13-15H21m-4.75 0l2 11m2-11l-2 11v8m-12.75-7l5-5m-4.75 2.75l2 2m.5-4.5l2 2m7-3.25h2");
}

</style>
