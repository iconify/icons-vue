<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zey5ebc0a"/><path class="b09_ctbde"/><path class="hzfx__bqu"/><path class="xq1pi7btv"/><path class="ng6jddb9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cdn-outline-bold" /></template>
<style>
.b09_ctbde {
  d: path("M2 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hzfx__bqu {
  d: path("M18 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ng6jddb9r {
  d: path("M18 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xq1pi7btv {
  d: path("M2 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zey5ebc0a {
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
