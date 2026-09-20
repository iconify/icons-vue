<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ftqzjnb8u"/><path class="rwo6s1bco"/><path class="nyn6oyb6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dns-outline-thin" /></template>
<style>
.ftqzjnb8u {
  d: path("M6 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nyn6oyb6w {
  d: path("M8 13a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2 2 2 0 0 1 -2 2h-6a2 2 0 0 1 -2 -2");
}

.rwo6s1bco {
  d: path("M8 6a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2 2 2 0 0 1 -2 2h-9a2 2 0 0 1 -2 -2");
}

</style>
