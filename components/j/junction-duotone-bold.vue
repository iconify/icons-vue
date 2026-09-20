<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bx5f_866s"/><path class="py9xm9zor"/><path class="m7_xl321u"/><path class="n7jp03moa"/><path class="gp7a30zvr"/><path class="o7mb9vbwf"/><path class="x_6spmb5u"/><path class="cfwe2fbcx"/><path class="gaonsmbbz"/><path class="v3qgglbcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:junction-duotone-bold" /></template>
<style>
.bx5f_866s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 2v6H2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cfwe2fbcx {
  d: path("M8 22v-6H2");
}

.gaonsmbbz {
  d: path("M16 22v-6h6");
}

.gp7a30zvr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9.5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m7_xl321u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 22v-6H2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n7jp03moa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 22v-6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o7mb9vbwf {
  d: path("M8 2v6H2");
}

.py9xm9zor {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 2v6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v3qgglbcl {
  d: path("M12 9.5v5");
}

.x_6spmb5u {
  d: path("M16 2v6h6");
}

</style>
