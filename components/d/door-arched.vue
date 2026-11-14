<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k7dbyrb5g"/><path class="sa4gg8hni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:door-arched" /></template>
<style>
.k7dbyrb5g {
  d: path("M4 21.5V10a8 8 0 0 1 16 0v11.5");
}

.sa4gg8hni {
  d: path("M7 21.5v-11a5 5 0 0 1 10 0v11m-14.5 0h19m-7.5-6h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
