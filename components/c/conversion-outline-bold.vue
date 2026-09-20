<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bqn9n10jh"/><path class="y8yw5pt-w"/><path class="ro0ipo0zu"/><path class="oe-s_bbxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:conversion-outline-bold" /></template>
<style>
.bqn9n10jh {
  d: path("M3 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.oe-s_bbxg {
  d: path("m18.5 15 3.5 3.5 -3.5 3.5 -3.5 -3.5Z");
}

.ro0ipo0zu {
  d: path("M14.5 11.5v3h-3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y8yw5pt-w {
  d: path("m10 10 2 2");
}

</style>
