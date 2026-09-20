<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r0jamibkm"/><path class="bn_pu6j-z"/><path class="lcdiu5g_w"/><path class="mihda9d9w"/><path class="u-hmh_b8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:eval-dataset-duotone-bold" /></template>
<style>
.bn_pu6j-z {
  d: path("M20 7v13H4V4h5l3 3h4");
}

.lcdiu5g_w {
  d: path("M9 11v6");
}

.mihda9d9w {
  d: path("M12 9v8");
}

.r0jamibkm {
  fill: currentColor;
  d: path("M20 7v13H4V4h5l3 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u-hmh_b8z {
  d: path("M15 12v5");
}

</style>
