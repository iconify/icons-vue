<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hrmjxqbnv"/><path class="cj3xrvjwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:genome-sequence" /></template>
<style>
.cj3xrvjwb {
  d: path("M3 9c4.5 0 4.5-6 9-6s4.5 6 9 6M3 13h6m3 0h9M3 17h3m3 0h8M3 21h10m3 0h5");
}

.hrmjxqbnv {
  d: path("M3 3c4.5 0 4.5 6 9 6s4.5-6 9-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
