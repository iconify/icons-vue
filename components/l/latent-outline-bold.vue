<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q-mksftst"/><path class="pfioxebak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:latent-outline-bold" /></template>
<style>
.pfioxebak {
  d: path("M21 4.5 13.5 12l7.5 7.5Z");
}

.q-mksftst {
  d: path("m3 4.5 7.5 7.5L3 19.5Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
