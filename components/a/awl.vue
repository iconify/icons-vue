<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjfero6xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:awl" /></template>
<style>
.kjfero6xq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.818 16.646l2.828-2.828a2.5 2.5 0 0 1 3.536 0a2.5 2.5 0 0 1 0 3.536l-2.828 2.828a2.5 2.5 0 0 1-3.536 0a2.5 2.5 0 0 1 0-3.536m6.432-2.896L21 3");
}

</style>
