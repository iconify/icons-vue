<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wsjhbwqgn"/><path class="gknxd_b4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:magazine-heart" /></template>
<style>
.gknxd_b4j {
  d: path("m18 21.5l-2.5-2.75A1.75 1.75 0 1 1 18 16.5a1.75 1.75 0 1 1 2.5 2.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wsjhbwqgn {
  d: path("M13.2 20.5H4v-18h14V13M7 6.5h8m-8 4h4.5");
}

</style>
