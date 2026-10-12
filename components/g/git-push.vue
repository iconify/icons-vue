<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xmjlrzbuo"/><path class="rpt7tg9rn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-push" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rpt7tg9rn {
  d: path("M5.75 3.25h12.5m-6.25 11V7m-3.25 3L12 6.75L15.25 10");
}

.xmjlrzbuo {
  cx: 12px;
  cy: 17.75px;
  r: 2.75px;
}

</style>
