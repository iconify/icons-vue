<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zm77yabat"/><path class="an26gneqy"/><path class="m6trofguq"/><path class="a249dcbsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:activity-ring-duotone-bold" /></template>
<style>
.a249dcbsw {
  d: path("M12 6.5A5.5 5.5 0 1 1 6.5 12");
}

.an26gneqy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6.5A5.5 5.5 0 1 1 6.5 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m6trofguq {
  d: path("M12 21a9 9 0 1 1 9 -9");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zm77yabat {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 21a9 9 0 1 1 9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
