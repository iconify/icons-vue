<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pp5zqibxy"/><path class="ojgy5rbdj"/><path class="m8ibkexva"/><path class="ht74g2xqg"/><path class="ph1z-dbce"/><path class="bbxz-u7vo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hearing-aid-duotone-bold" /></template>
<style>
.bbxz-u7vo {
  d: path("M16 6a6 6 0 0 1 0 12");
}

.ht74g2xqg {
  d: path("M6 20A6 6 0 0 1 6 8a4 4 0 0 1 6 8");
}

.m8ibkexva {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 6a6 6 0 0 1 0 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ojgy5rbdj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 9a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ph1z-dbce {
  d: path("M16 9a3 3 0 0 1 0 6");
}

.pp5zqibxy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 20A6 6 0 0 1 6 8a4 4 0 0 1 6 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
