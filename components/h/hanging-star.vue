<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8x38wg-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hanging-star" /></template>
<style>
.j8x38wg-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 7.5l2.057 4.168l4.6.669l-3.328 3.245l.785 4.581L12 18l-4.114 2.163l.785-4.581l-3.328-3.245l4.6-.669Zm0-5v5");
}

</style>
