<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="kqef4tbqv"/><path class="jedknxkfu"/><circle class="l1sa2pbgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jhumka" /></template>
<style>
.jedknxkfu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5v2m-6 6a6 6 0 0 1 12 0Zm6 0v3.25");
}

.kqef4tbqv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3.25h.01");
}

.l1sa2pbgo {
  cx: 12px;
  cy: 18.5px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
