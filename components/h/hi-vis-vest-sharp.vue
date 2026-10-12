<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_dab6b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hi-vis-vest-sharp" /></template>
<style>
.t_dab6b8d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 2.75H10l.38 1.19l1.24 3.87L12 9l.38-1.19l1.24-3.87l.38-1.19h2.5l.68 1.05l2.39 3.65l.68 1.05v12.75H3.75V8.5l.68-1.05L6.82 3.8l.68-1.05zm-5 10.5h16.5m-16.5 4h16.5");
}

</style>
