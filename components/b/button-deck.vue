<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bzr1dpb5e"/><path class="vkt_78dss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:button-deck" /></template>
<style>
.bzr1dpb5e {
  d: path("M6.875 4h10.25A4.375 4.375 0 0 1 21.5 8.375v7.25A4.375 4.375 0 0 1 17.125 20H6.875A4.375 4.375 0 0 1 2.5 15.625v-7.25A4.375 4.375 0 0 1 6.875 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vkt_78dss {
  d: path("M7 6.75h1A1.75 1.75 0 0 1 9.75 8.5A1.75 1.75 0 0 1 8 10.25H7A1.75 1.75 0 0 1 5.25 8.5A1.75 1.75 0 0 1 7 6.75m9 0h1a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 17 10.25h-1a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 16 6.75m-9 7h1a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 8 17.25H7a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 7 13.75m9 0h1a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 17 17.25h-1a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 16 13.75");
}

</style>
