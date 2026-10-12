<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucoh6rbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:expand-sharp" /></template>
<style>
.ucoh6rbng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 12h15.5M12 9V3.75M8.75 7L12 3.75L15.25 7M12 15v5.25M8.75 17L12 20.25L15.25 17");
}

</style>
