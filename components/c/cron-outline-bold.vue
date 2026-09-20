<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a0ad3xbzg"/><path class="v2c2asm0d"/><path class="icp673bbo"/><path class="dm5ccobgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cron-outline-bold" /></template>
<style>
.a0ad3xbzg {
  d: path("M12 3a9 9 0 1 0 9 9");
}

.dm5ccobgo {
  d: path("M12 12h4");
}

.icp673bbo {
  d: path("M12 9v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v2c2asm0d {
  d: path("M21 4v5h-5");
}

</style>
