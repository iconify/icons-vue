<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iuvcd7b5n"/><path class="jren1ny6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:afternoon-tea" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iuvcd7b5n {
  d: path("M5 9.5h11v3a5 5 0 0 1-5 5h-1a5 5 0 0 1-5-5Z");
}

.jren1ny6c {
  d: path("M16 10.5h1.25a2 2 0 0 1 0 4H15.5M3 20.5h16M8.5 3q-1 1.75 0 3.5m4-3.5q-1 1.75 0 3.5");
}

</style>
