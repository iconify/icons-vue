<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vbvr2ebxa"/><path class="uk0rveqaj"/><path class="xcm-54bzl"/><path class="a6m5kfb7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bass-clef-outline-bold" /></template>
<style>
.a6m5kfb7k {
  d: path("M18 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uk0rveqaj {
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vbvr2ebxa {
  d: path("M7 6c4 0 8 2 8 6s-4 7 -8 8");
}

.xcm-54bzl {
  d: path("M18 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
