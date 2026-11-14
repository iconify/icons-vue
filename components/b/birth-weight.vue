<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g2egpfbik"/><path class="abhg91bdx"/><path class="wdrefqfmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:birth-weight" /></template>
<style>
.abhg91bdx {
  fill: currentColor;
  d: path("M10.25 17.5a1.75 2.25 0 1 0 3.5 0a1.75 2.25 0 1 0-3.5 0Z");
}

.g2egpfbik {
  d: path("M4 21.5L7 10h10l3 11.5ZM9.5 6.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wdrefqfmw {
  d: path("M10.25 13.75h.01m1.74-.5h.01m1.74.5h.01");
}

</style>
