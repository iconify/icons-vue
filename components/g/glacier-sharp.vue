<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs2u6d_av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:glacier-sharp" /></template>
<style>
.rs2u6d_av {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.59 14.19l6.82-9.38L12 4l.59.81l6.82 9.38l.59.81H4zM2.75 20c1.54 0 1.54-1 3.08-1s1.54 1 3.08 1s1.54-1 3.08-1s1.54 1 3.08 1s1.54-1 3.08-1s1.54 1 3.08 1");
}

</style>
