<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z-ojm5bbd"/><path class="kc1yf3bro"/><path class="xemh9nb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ball-head" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kc1yf3bro {
  d: path("M6.5 11a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.xemh9nb-o {
  d: path("M10.25 16.25v5.25h3.5v-5.25");
}

.z-ojm5bbd {
  d: path("M6.5 2.5h11A1.5 1.5 0 0 1 19 4a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 4a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
