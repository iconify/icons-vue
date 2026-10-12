<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="toocmmbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gold-bars-sharp" /></template>
<style>
.toocmmbst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 19.53l1-3.81l.25-.97h5l.25.97l1 3.81l.25.97h-8zm10.5 0l1-3.81l.25-.97h5l.25.97l1 3.81l.25.97h-8zM8 11.28l1-3.81l.25-.97h5.5l.25.97l1 3.81l.25.97h-8.5z");
}

</style>
