<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t7scrr-5w"/><path class="p8iop6bwz"/><path class="lcuc7cckr"/><path class="l6rre7bha"/><path class="b2kor_b2y"/><path class="agr8d8b-b"/><path class="gfyw8vbbf"/><path class="d-v-f28sf"/><path class="c-xj8zban"/><path class="q1jaj6b2n"/><path class="chx4f6b7j"/><path class="y69n27oio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-graph-duotone-bold" /></template>
<style>
.agr8d8b-b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20 15 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b2kor_b2y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 15 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c-xj8zban {
  d: path("M20 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.chx4f6b7j {
  d: path("m14 15 2 2");
}

.d-v-f28sf {
  d: path("M12 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gfyw8vbbf {
  d: path("M7.69 2.37a4 4 0 1 1 -3.38 0");
}

.l6rre7bha {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.69 2.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lcuc7cckr {
  fill: currentColor;
  d: path("M16 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.p8iop6bwz {
  fill: currentColor;
  d: path("M20 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q1jaj6b2n {
  d: path("M16 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t7scrr-5w {
  fill: currentColor;
  d: path("M12 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y69n27oio {
  d: path("m20 15 -2 2");
}

</style>
