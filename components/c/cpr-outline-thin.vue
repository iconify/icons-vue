<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="feh5q_b1s"/><path class="wgzf3kbdp"/><path class="w7dz13y2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cpr-outline-thin" /></template>
<style>
.feh5q_b1s {
  d: path("M5 14a3.5 3.5 0 0 1 7 0 3.5 3.5 0 0 1 7 0l-7 7Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w7dz13y2v {
  d: path("m8 2 4 4 4 -4");
}

.wgzf3kbdp {
  d: path("m8 6 4 4 4 -4");
}

</style>
