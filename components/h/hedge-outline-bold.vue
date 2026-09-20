<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o8hzclkqx"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hedge-outline-bold" /></template>
<style>
.jkuojibnm {
  d: path("M3 20h18");
}

.o8hzclkqx {
  d: path("M3 17v-5c0 -4 4 -7 9 -7s9 3 9 7v5Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
