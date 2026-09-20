<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hwufvfb8q"/><path class="y7d5mpfbz"/><path class="y334m4yqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-front-outline-bold" /></template>
<style>
.hwufvfb8q {
  d: path("M3 20v-8l9 -9 9 9v8Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y334m4yqh {
  d: path("M9 8h6v4H9Z");
}

.y7d5mpfbz {
  d: path("M10 20v-5h4v5");
}

</style>
