<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="v3x3kdbao"/><path class="u3o-46mas"/><circle class="lreqg6b4y"/><path class="d9gv9881c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mahjong-tile" /></template>
<style>
.d9gv9881c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.75h.01");
}

.lreqg6b4y {
  cx: 12px;
  cy: 9.75px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u3o-46mas {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 17.25h14.5");
}

.v3x3kdbao {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
