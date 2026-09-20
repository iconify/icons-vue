<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abnm6smsv"/><path class="u84sg0ngq"/><path class="a2e335b1o"/><path class="h857n5bhq"/><path class="fmjpvzbts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:instruction-outline-thin" /></template>
<style>
.a2e335b1o {
  d: path("M11 10h5");
}

.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.fmjpvzbts {
  d: path("M11 14h5");
}

.h857n5bhq {
  d: path("M8 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u84sg0ngq {
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
