<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uhsn5wb8z"/><path class="djz5e420y"/><path class="ildco7byy"/><path class="kcvg8_brd"/><path class="riqqdm93h"/><path class="wnk6eob9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:humidity-high-duotone-bold" /></template>
<style>
.djz5e420y {
  fill: currentColor;
  d: path("m15 11 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ildco7byy {
  fill: currentColor;
  d: path("m11 16 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kcvg8_brd {
  d: path("m8 7 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

.riqqdm93h {
  d: path("m15 11 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uhsn5wb8z {
  fill: currentColor;
  d: path("m8 7 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wnk6eob9l {
  d: path("m11 16 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

</style>
