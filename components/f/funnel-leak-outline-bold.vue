<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bdb2pqp3q"/><path class="d05ifsb6w"/><path class="bytnyw6tw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:funnel-leak-outline-bold" /></template>
<style>
.bdb2pqp3q {
  d: path("M3 3h18l-7 7v6h-4v-6Z");
}

.bytnyw6tw {
  d: path("M19.5 16v2.5");
}

.d05ifsb6w {
  d: path("M17.5 12v2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
