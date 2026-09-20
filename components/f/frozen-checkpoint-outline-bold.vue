<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="zofa9qbxh"/><path class="gn1ganbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:frozen-checkpoint-outline-bold" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.gn1ganbdv {
  d: path("M10.5 10a1.5 1.5 0 0 1 3 0");
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zofa9qbxh {
  d: path("M9 10h6v3H9Z");
}

</style>
