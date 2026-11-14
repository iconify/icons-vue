<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xjxxwsbnq"/><path class="aov7-_bpd"/><path class="u5eh67bxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-line-target" /></template>
<style>
.aov7-_bpd {
  fill: currentColor;
  d: path("M17.5 2.5L21 4l-3.5 1.5Z");
}

.u5eh67bxn {
  d: path("M2.5 9h2M7 9h2m2.5 0h2m6.25 0h1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xjxxwsbnq {
  d: path("M2.5 20L7 14.5l3.5 2l5-6.5m2-1V2.5");
}

</style>
