<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su0h_pb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eye-wash-sharp" /></template>
<style>
.su0h_pb4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12.25h16.5a8.25 3.5 0 0 1-16.5 0Zm8.25 3.5v5.5m-3.5 0h7m-7-9V10m7 2.25V10m-7-1.75V6.083L10 4.25m5.5 4V6.083L14 4.25");
}

</style>
