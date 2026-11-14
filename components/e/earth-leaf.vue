<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dplbpebxb"/><path class="kn5iicbvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:earth-leaf" /></template>
<style>
.dplbpebxb {
  d: path("M2.5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

.kn5iicbvl {
  d: path("M6.5 9.5a3 7 0 1 0 6 0a3 7 0 1 0-6 0Zm-4 0h14M16 20c0-3.5 1.5-5 5-5c0 3.5-1.5 5-5 5Zm0 0l-1.25 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
