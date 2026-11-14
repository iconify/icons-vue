<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hmz9tgk5g"/><path class="ji_jn_bpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cognitive-therapy" /></template>
<style>
.hmz9tgk5g {
  d: path("M7.75 10.75c.5-1.75 2.25-2.5 4-2c1-1 3.5-.75 4.25.5c2 0 3.25 1.5 3 3.25c1.25 1 1.25 3.25.25 4.25a2.652 2.652 0 0 1-3 3c-.75 1.25-3 1.75-4.25.75c-1.5 1-3.5.5-4.25-.75c-2 .25-3.5-1.25-3-3c-1-1-1-3.25.25-4c0-1.5 1.25-2.5 2.75-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ji_jn_bpa {
  d: path("M5.75 16.5c2.5-1 5 .25 7.5-1.25m-.75-6.5c-.75 1.5.5 2.75 0 4.5m3 4.25c1-.75 2.25-.5 2.75-1.75M5.5 4.5h13M4.25 2.25zA1.25 1.25 0 0 1 5.5 3.5v2a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 3 5.5v-2a1.25 1.25 0 0 1 1.25-1.25m15.5 0zA1.25 1.25 0 0 1 21 3.5v2a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 18.5 5.5v-2a1.25 1.25 0 0 1 1.25-1.25M8.5 9.5l-.5-5M16 9l.25-4.5");
}

</style>
