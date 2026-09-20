<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="bk1dirtva"/><path class="dgqc-wbei"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="ns_05qbai"/><path class="zm2dyvb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:baseline-approve-duotone-bold" /></template>
<style>
.bk1dirtva {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 11 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c1kziyotx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.dgqc-wbei {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hieqhxiaw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.ns_05qbai {
  d: path("m9 11 2 2 4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zm2dyvb-o {
  d: path("M9 16h6");
}

</style>
