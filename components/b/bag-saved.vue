<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q2p3s81fv"/><path class="ajl3_fqgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bag-saved" /></template>
<style>
.ajl3_fqgg {
  d: path("M18 21c-1.5-1-3-2.25-3-4c0-1 .75-1.75 1.75-1.75c.65 0 1.05.35 1.25.75c.2-.4.6-.75 1.25-.75c.95 0 1.75.75 1.75 1.75c0 1.75-1.5 3-3 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q2p3s81fv {
  d: path("M5 8h14l-.5 4.25h-4.25a2 2 0 0 0-2 2V21h-4.5a2 2 0 0 1-2-2Zm3.5 0V6.5a3.5 3.5 0 0 1 7 0V8");
}

</style>
