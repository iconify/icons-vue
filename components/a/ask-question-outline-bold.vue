<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cu90avb1w"/><path class="l3ce2kb5n"/><path class="x5yyblbox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ask-question-outline-bold" /></template>
<style>
.cu90avb1w {
  d: path("M4 4h14a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2h-6l-4 4v-4H4a2 2 0 0 1 -2 -2V6a2 2 0 0 1 2 -2");
}

.l3ce2kb5n {
  d: path("M9 8a2.5 2.5 0 0 1 5 0c0 2 -2.5 2 -2.5 3.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x5yyblbox {
  d: path("M10.5 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
