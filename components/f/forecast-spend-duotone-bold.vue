<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxjvqtiry"/><path class="o6_m2lbfu"/><path class="nps6jz3so"/><path class="qe97cg-lx"/><path class="u27h90bpp"/><path class="yqoazhbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:forecast-spend-duotone-bold" /></template>
<style>
.nps6jz3so {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.5 5H19v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o6_m2lbfu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 18 6 -6 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u27h90bpp {
  d: path("m6 18 6 -6 7 -7");
}

.yqoazhbqh {
  d: path("M15.5 5H19v3.5");
}

.yxjvqtiry {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
