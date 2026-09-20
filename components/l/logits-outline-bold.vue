<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ohbum8bmx"/><path class="b2pxrbbhs"/><path class="nu6kj0bjf"/><path class="xyj-l9cjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:logits-outline-bold" /></template>
<style>
.b2pxrbbhs {
  d: path("M11 5v13");
}

.nu6kj0bjf {
  d: path("M16 11v7");
}

.ohbum8bmx {
  d: path("M6 8v10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
