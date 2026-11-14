<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lq-t_kbrm"/><path class="kyfeqdbjf"/><path class="fzfakj39n"/><path class="tupbhegqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fever-child" /></template>
<style>
.fzfakj39n {
  fill: currentColor;
  d: path("M9 7h6a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 15 10H9a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kyfeqdbjf {
  d: path("M11.5 4.5c-.5-1.5 1.25-2 1.75-1");
}

.lq-t_kbrm {
  d: path("M3.5 13a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0");
}

.tupbhegqk {
  d: path("M9 13h.01M15 13h.01M10 16.5c1.25.75 2.75.75 4 0");
}

</style>
