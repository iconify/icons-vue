<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bozx6abjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:haptic-feedback-sharp" /></template>
<style>
.bozx6abjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 2.75h5.5v12.5a2.75 2.75 0 0 1-5.5 0Zm1.5 4.75h2.5M2.75 21.25h18.5M7 14.25a5 5 0 0 0 0 5M4.25 12.5a8 8 0 0 0 0 7.25M17 14.25a5 5 0 0 1 0 5m2.75-6.75a8 8 0 0 1 0 7.25");
}

</style>
