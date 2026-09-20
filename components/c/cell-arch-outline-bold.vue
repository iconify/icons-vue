<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jutdvybnj"/><path class="wumf77bxt"/><path class="wi71wvbqq"/><path class="bg56fj76r"/><path class="a6z1jcjqs"/><path class="ivqg9reic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cell-arch-outline-bold" /></template>
<style>
.a6z1jcjqs {
  d: path("M8 16a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.bg56fj76r {
  d: path("M16.5 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ivqg9reic {
  d: path("M11 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.jutdvybnj {
  d: path("M2.5 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wi71wvbqq {
  d: path("M13.5 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.wumf77bxt {
  d: path("M5.5 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
