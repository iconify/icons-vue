<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="axwkrzbmo"/><path class="nuz6-76is"/><path class="zl61012kd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:decoder-only-outline-thin" /></template>
<style>
.axwkrzbmo {
  d: path("m8 8 4 4 -4 4 -4 -4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nuz6-76is {
  d: path("M15 12h6");
}

.zl61012kd {
  d: path("M18.5 9.5 21 12l-2.5 2.5");
}

</style>
