<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="czu33icqx"/><path class="s7lu65m3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crystal-ball-clear" /></template>
<style>
.czu33icqx {
  d: path("M4.5 10a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s7lu65m3v {
  d: path("M9.332 16.5h5.336a1.75 1.75 0 0 1 1.566.967l.641 1.283A1.555 1.555 0 0 1 15.484 21H8.516a1.555 1.555 0 0 1-1.391-2.25l.641-1.283a1.75 1.75 0 0 1 1.566-.967M7.5 10a4.5 4.5 0 0 1 2.961-4.229");
}

</style>
