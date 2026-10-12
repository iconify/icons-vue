<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h7pzwctkf"/><circle class="ydy0opbpr"/><path class="bcsod8b9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:birthday-kid" /></template>
<style>
.bcsod8b9c {
  d: path("M9.75 14.25v.5m4.5-.5v.5m-4 2.75c1 .9 2.5.9 3.5 0");
}

.h7pzwctkf {
  d: path("m8.42 11l3.18-7.1q.4-.9.8 0l3.18 7.1a5.75 5.75 0 0 0-7.16 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydy0opbpr {
  cx: 12px;
  cy: 15.5px;
  r: 5.75px;
}

</style>
