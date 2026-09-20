<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uw5kuce7r"/><path class="lps9qspxb"/><path class="zdricccut"/><path class="hc853a05m"/><path class="c6hn90blm"/><path class="b_5ug6ank"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bellhop-outline-bold" /></template>
<style>
.b_5ug6ank {
  d: path("M17 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.c6hn90blm {
  d: path("M8 20.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hc853a05m {
  d: path("M7 13.5h13");
}

.lps9qspxb {
  d: path("M3 3h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uw5kuce7r {
  d: path("M3 3v18");
}

.zdricccut {
  d: path("M7 18V9h13v9Z");
}

</style>
