<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sigkrwbsn"/><path class="firku7bll"/><path class="ivnye2b_d"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:carrom-board-sharp" /></template>
<style>
.firku7bll {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 6.25h.01m11.49 0h.01M6.25 17.75h.01m11.49 0h.01");
}

.ivnye2b_d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m.5 5.75h6M9 6.25h6");
}

.sigkrwbsn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h18v18H3z");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
