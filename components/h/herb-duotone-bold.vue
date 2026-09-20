<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cw_6xibvp"/><path class="sjw1pmbjk"/><path class="mnwr0qhch"/><path class="hc0aulbwc"/><path class="fmqqksbgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:herb-duotone-bold" /></template>
<style>
.cw_6xibvp {
  fill: currentColor;
  d: path("M12 9C8 9 6 7 6 4c4 0 6 2 6 5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fmqqksbgb {
  d: path("M12 14c4 0 6 -2 6 -5 -4 0 -6 2 -6 5");
}

.hc0aulbwc {
  d: path("M12 9C8 9 6 7 6 4c4 0 6 2 6 5");
}

.mnwr0qhch {
  d: path("M12 4v17");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sjw1pmbjk {
  fill: currentColor;
  d: path("M12 14c4 0 6 -2 6 -5 -4 0 -6 2 -6 5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
