<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wdd_k9f2l"/><path class="iyr5jibbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:glass-recycle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iyr5jibbw {
  d: path("M11 6.5h2V9c1.5.6 2.25 1.75 2.25 3.25v4.5A1.25 1.25 0 0 1 14 18h-4a1.25 1.25 0 0 1-1.25-1.25v-4.5c0-1.5.75-2.65 2.25-3.25Z");
}

.wdd_k9f2l {
  d: path("M16.5 4.21a9 9 0 1 1-9 0m-.65 2.42l.65-2.42l-2.42-.65");
}

</style>
