<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uea3q0bms"/><path class="b-bvkjb9c"/><path class="n81iwfhmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agility-tunnel" /></template>
<style>
.b-bvkjb9c {
  d: path("M5 6.75q7-3 14 0m-14 12q7-3 14 0m0-12a2.5 6 0 0 1 0 12");
}

.n81iwfhmj {
  d: path("M12 5.25a2.5 6 0 0 1 0 12");
}

.uea3q0bms {
  d: path("M2.5 12.75a2.5 6 0 1 0 5 0a2.5 6 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
