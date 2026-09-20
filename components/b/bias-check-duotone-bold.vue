<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q7kmvtbzo"/><path class="xpq25bwol"/><path class="ec3wf9bhi"/><path class="rsui_05gv"/><path class="q2i8lfb2i"/><path class="atzi6u7-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bias-check-duotone-bold" /></template>
<style>
.atzi6u7-j {
  d: path("m14 16 3 3 5 -5");
}

.ec3wf9bhi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 16 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q2i8lfb2i {
  d: path("M4 13h10");
}

.q7kmvtbzo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rsui_05gv {
  d: path("M4 8h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xpq25bwol {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 13h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
