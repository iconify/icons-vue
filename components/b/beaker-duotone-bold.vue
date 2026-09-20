<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c-_wbo04r"/><path class="o9nm0ibif"/><path class="dnw1zac9y"/><path class="ashxj_7io"/><path class="z26jhbbft"/><path class="z8g2jgblp"/><path class="jyz8nlkxs"/><path class="dpjt_8byn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:beaker-duotone-bold" /></template>
<style>
.ashxj_7io {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c-_wbo04r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 5v15h14V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dnw1zac9y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dpjt_8byn {
  d: path("M17 5h4");
}

.jyz8nlkxs {
  d: path("M3 5h4");
}

.o9nm0ibif {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z26jhbbft {
  d: path("M5 5v15h14V5");
}

.z8g2jgblp {
  d: path("M5 12h14");
}

</style>
