<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="dgzxj0b0g"/><circle class="lreqg6b4y"/><path class="d9gv9881c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mahjong-tile-sharp" /></template>
<style>
.d9gv9881c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.75h.01");
}

.dgzxj0b0g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h14.5v18.5H4.75zm0 14.5h14.5");
}

.lreqg6b4y {
  cx: 12px;
  cy: 9.75px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
