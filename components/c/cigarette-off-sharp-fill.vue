<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="t2woffbwj"/><path class="ja_h_hb8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cigarette-off-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ja_h_hb8o {
  d: path("M15 3H16C17.657 3 19 4.343 19 6V7.5M19 7.5C20.657 7.5 22 8.843 22 10.5V13M19 7.5H16.5M1.707 1.707L22.293 22.293");
}

.t2woffbwj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 19V21C19 21.552 18.552 22 18 22H2C1.448 22 1 21.552 1 21V16C1 15.448 1.448 15 2 15H15L19 19Z");
  stroke: none;
}

</style>
