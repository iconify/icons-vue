<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iwlv39tfz"/><path class="kjp1db1zf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:front-loader-cargo-bike" /></template>
<style>
.iwlv39tfz {
  d: path("M2.5 17.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm12.5 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM11.5 4.5H13v7.75h8.5V7.5");
}

.kjp1db1zf {
  d: path("M5.25 17.75H9.5l3.5-5.5m-3.5 5.5l-2-7.25m-1.5 0h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
