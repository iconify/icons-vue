<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xaafqhbdh"/><path class="uuhg5tbuk"/><path class="rjnrdobeg"/><path class="rcu9plbzq"/><path class="sm8qqabeo"/><path class="ex075abcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:class-balance-outline-bold" /></template>
<style>
.ex075abcq {
  d: path("M16.5 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.rcu9plbzq {
  d: path("M14 7a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.rjnrdobeg {
  d: path("M5.5 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sm8qqabeo {
  d: path("M16.5 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.uuhg5tbuk {
  d: path("M5.5 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.xaafqhbdh {
  d: path("M3 7a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
