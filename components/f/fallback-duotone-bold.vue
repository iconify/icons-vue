<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ditq3ccrr"/><path class="pnyhwuqhh"/><path class="sbiy6014w"/><path class="c46fyy1pe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fallback-duotone-bold" /></template>
<style>
.c46fyy1pe {
  d: path("m16 12 3 3 -3 3");
}

.ditq3ccrr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 7h9v8h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pnyhwuqhh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 12 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sbiy6014w {
  d: path("M3 7h9v8h7");
}

</style>
