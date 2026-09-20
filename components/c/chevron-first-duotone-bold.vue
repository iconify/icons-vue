<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i-xhowkfx"/><path class="v6rblft4s"/><path class="nxab-kxlu"/><path class="yr0a_60jr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevron-first-duotone-bold" /></template>
<style>
.i-xhowkfx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nxab-kxlu {
  d: path("M3 5v14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v6rblft4s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 5 -7 7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yr0a_60jr {
  d: path("m19 5 -7 7 7 7");
}

</style>
