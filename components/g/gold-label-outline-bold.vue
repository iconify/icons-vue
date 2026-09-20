<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fe9c5cduf"/><path class="ma7lidmyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gold-label-outline-bold" /></template>
<style>
.fe9c5cduf {
  d: path("M3 7h13l5 5 -5 5H3Z");
}

.ma7lidmyb {
  d: path("m6 12 2 2 3.5 -3.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
