<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l2el_bbjq"/><path class="uzdw-e_ie"/><path class="hca97abqo"/><path class="n-6o3ubsz"/><path class="bm-eye5hu"/><path class="r8eifzb3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hiking-trail-duotone-bold" /></template>
<style>
.bm-eye5hu {
  d: path("M7 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hca97abqo {
  fill: currentColor;
  d: path("M12 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l2el_bbjq {
  fill: currentColor;
  d: path("M8 4a4 4 0 0 1 8 0v9a4 4 0 0 1 -8 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n-6o3ubsz {
  d: path("M8 4a4 4 0 0 1 8 0v9a4 4 0 0 1 -8 0Z");
}

.r8eifzb3i {
  d: path("M12 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uzdw-e_ie {
  fill: currentColor;
  d: path("M7 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
