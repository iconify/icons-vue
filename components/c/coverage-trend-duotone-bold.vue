<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="ir7pwtbvt"/><path class="rryylcb5h"/><path class="qoyxknbjl"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="fs--blxyx"/><path class="xxenxccpt"/><path class="hlt9oudyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coverage-trend-duotone-bold" /></template>
<style>
.c1kziyotx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.fs--blxyx {
  d: path("M9 13v3");
}

.hieqhxiaw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hlt9oudyd {
  d: path("M15 9v7");
}

.ir7pwtbvt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 13v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.qoyxknbjl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rryylcb5h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 11v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xxenxccpt {
  d: path("M12 11v5");
}

</style>
