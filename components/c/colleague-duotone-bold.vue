<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wnz9a7lxg"/><path class="tyxow4b3g"/><path class="k2jzr9u7f"/><path class="qnck32bfn"/><path class="gliukfoxr"/><path class="jjma1jbuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:colleague-duotone-bold" /></template>
<style>
.gliukfoxr {
  d: path("M14 12v8h8v-8Z");
}

.jjma1jbuu {
  d: path("M16 12V9h4v3");
}

.k2jzr9u7f {
  d: path("M5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.qnck32bfn {
  d: path("M4 16a4 4 0 0 1 8 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tyxow4b3g {
  fill: currentColor;
  d: path("M14 12v8h8v-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wnz9a7lxg {
  fill: currentColor;
  d: path("M5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
