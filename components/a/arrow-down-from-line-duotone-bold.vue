<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="px0mg1brp"/><path class="taifrj74e"/><path class="c76qbklkq"/><path class="t46_l1b3y"/><path class="o8adkomvn"/><path class="qrnoe1--b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-down-from-line-duotone-bold" /></template>
<style>
.c76qbklkq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 16 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o8adkomvn {
  d: path("M12 8v12");
}

.px0mg1brp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 4h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qrnoe1--b {
  d: path("m8 16 4 4 4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t46_l1b3y {
  d: path("M7 4h10");
}

.taifrj74e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
