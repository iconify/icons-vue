<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ljo-5rbrq"/><path class="g6ym9f7qk"/><path class="rv0me50po"/><path class="c7dgfu7wx"/><path class="oy6o-dbxk"/><path class="o1_lmbxyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:curtain-duotone-thin" /></template>
<style>
.c7dgfu7wx {
  d: path("M2 4h20");
}

.g6ym9f7qk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4v17h5c1.5 0 2 -1 2 -3V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ljo-5rbrq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o1_lmbxyf {
  d: path("M21 4v17h-5c-1.5 0 -2 -1 -2 -3V4");
}

.oy6o-dbxk {
  d: path("M3 4v17h5c1.5 0 2 -1 2 -3V4");
}

.rv0me50po {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 4v17h-5c-1.5 0 -2 -1 -2 -3V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
