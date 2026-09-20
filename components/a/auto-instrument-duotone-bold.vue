<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="iyu3ezo0y"/><path class="j9vnxwb5d"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="r182r524c"/><path class="c7z9o8buo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:auto-instrument-duotone-bold" /></template>
<style>
.c1kziyotx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c7z9o8buo {
  d: path("M7 15h10");
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.hieqhxiaw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iyu3ezo0y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 9h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j9vnxwb5d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 15h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.r182r524c {
  d: path("M7 9h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
