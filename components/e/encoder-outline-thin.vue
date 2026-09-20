<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ps3-67b_v"/><path class="wlia6bb5b"/><path class="adiugjbhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:encoder-outline-thin" /></template>
<style>
.adiugjbhs {
  d: path("m15 9 3 3 -3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ps3-67b_v {
  d: path("m4 3 6 6v6l-6 6");
}

.wlia6bb5b {
  d: path("M11 12h7");
}

</style>
