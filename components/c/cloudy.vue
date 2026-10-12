<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oncaxeeaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cloudy" /></template>
<style>
.oncaxeeaf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.61 19.89a3.44 3.44 0 0 1-.47-6.85a4.95 4.95 0 0 1 9.16-1.19a3.87 3.87 0 0 1-.52 8.04Zm3.9-13.23a2.5 2.5 0 0 1 1.24-.43m-.01 0a3.56 3.56 0 0 1 6.6-.87m.01.01a2.9 2.9 0 0 1 1.08 5.51");
}

</style>
