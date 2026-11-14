<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cw42627ol"/><path class="m8wbn48te"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:era-hourglass" /></template>
<style>
.cw42627ol {
  d: path("M7.5 3h9l-3.75 6.25l3.75 6.25h-9l3.75-6.25Zm-5 18.5v-2h2v-2h2v-2h11v2h2v2h2v2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m8wbn48te {
  fill: currentColor;
  d: path("m10.75 14l.098-.117a1.5 1.5 0 0 1 2.304 0l.098.117a.915.915 0 0 1-.703 1.5h-1.094a.915.915 0 0 1-.703-1.5");
}

</style>
