<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="meacokyks"/><path class="myjwprbgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coral-restoration" /></template>
<style>
.meacokyks {
  d: path("M8.5 17.5v-5Q8.5 10 5 9V4.5m3.5 8q0-2.5 4-3.5V4m0 5Q16 8.5 16 5");
}

.myjwprbgk {
  d: path("M3 21q4.605-5.861 9.21-1.908M18 15v6m-3-3h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
