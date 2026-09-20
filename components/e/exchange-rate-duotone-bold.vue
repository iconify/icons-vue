<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xnrghp1vk"/><path class="o-4bk_b4n"/><path class="o8od38cnm"/><path class="juq6zh-od"/><path class="qq2awqbbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:exchange-rate-duotone-bold" /></template>
<style>
.juq6zh-od {
  d: path("M6.5 15.5 4 18l2.5 2.5");
}

.o-4bk_b4n {
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8");
}

.o8od38cnm {
  d: path("M4 18h16");
}

.qq2awqbbs {
  d: path("M17.5 15.5 20 18l-2.5 2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xnrghp1vk {
  fill: currentColor;
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
