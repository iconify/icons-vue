<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ozusmjceo"/><path class="wimmg3bgi"/><path class="awmc0ybgj"/><path class="qfik3jxdk"/><path class="fuo4460wo"/><path class="ab69i60qd"/><path class="q4hnnr4zu"/><path class="ly2b2eaue"/><path class="lgk47ib7d"/><path class="gorvssbqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:kv-evict-duotone-bold" /></template>
<style>
.ab69i60qd {
  d: path("M5.5 4H3v16h2.5");
}

.awmc0ybgj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 4H3v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fuo4460wo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17.5 9.5 20 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gorvssbqo {
  d: path("M17.5 9.5 20 12l-2.5 2.5");
}

.lgk47ib7d {
  d: path("M14.5 12h3");
}

.ly2b2eaue {
  d: path("M8.5 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ozusmjceo {
  fill: currentColor;
  d: path("M8.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q4hnnr4zu {
  d: path("M8.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qfik3jxdk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.5 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wimmg3bgi {
  fill: currentColor;
  d: path("M8.5 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
