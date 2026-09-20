<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rmcfrrb-t"/><path class="oiqkce4vb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ice-hockey-outline-bold" /></template>
<style>
.oiqkce4vb {
  d: path("M13 5h6v4h-6Z");
}

.rmcfrrb-t {
  d: path("M6 3v12c0 3 2 4 5 4h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
