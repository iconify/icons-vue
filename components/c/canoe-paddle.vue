<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg4oyjduw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:canoe-paddle" /></template>
<style>
.zg4oyjduw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.718 5.282l-7.425 7.425m0 0za2.5 2.5 0 0 1 0 3.536l-2.475 2.475a2.5 2.5 0 0 1-3.536 0a2.5 2.5 0 0 1 0-3.536l2.475-2.475a2.5 2.5 0 0 1 3.536 0m6.01-8.839l2.829 2.829");
}

</style>
