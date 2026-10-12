<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4sh5mbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barrier-fence-sharp" /></template>
<style>
.w4sh5mbsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.5h18.5V12H2.75zM7 12l4-6.5m2 6.5l4-6.5M6 12v8.5M18 12v8.5m-14.75 0h5.5m6.5 0h5.5");
}

</style>
