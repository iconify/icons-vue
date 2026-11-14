<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aoqruxhyf"/><path class="tsm53-xwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blood-sugar" /></template>
<style>
.aoqruxhyf {
  d: path("M11.683 18.322a5.8 5.8 0 0 1-2.183.428c-3.25 0-6-2.75-6-6c0-3.5 3-6.5 6-10.25c2.89 3.612 5.779 6.528 5.988 9.866m3.183 2.219l2 1a1.5 1.5 0 0 1 .829 1.342v2.146a1.5 1.5 0 0 1-.829 1.342l-2 1a1.5 1.5 0 0 1-1.342 0l-2-1a1.5 1.5 0 0 1-.829-1.342v-2.146a1.5 1.5 0 0 1 .829-1.342l2-1a1.5 1.5 0 0 1 1.342 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tsm53-xwj {
  d: path("m14.5 16l3.5 1.75L21.5 16M18 17.75v4");
}

</style>
