<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nlmmeubzn"/><path class="s0fao209o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:falling-rocks" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nlmmeubzn {
  d: path("M4 3v18h16");
}

.s0fao209o {
  d: path("m7.79 5.63l.38-.24q.67-.43 1.41-.12l.41.17q.74.31.61 1.1l-.07.4q-.14.79-.89 1.04l-.69.23q-.75.26-1.08-.47l-.42-.94q-.33-.73.34-1.17m4.9 5.14l.33-.21q.59-.38 1.24-.11l.36.15q.65.28.53.96l-.06.35q-.12.69-.78.92l-.6.2q-.66.23-.95-.41l-.37-.83q-.28-.64.3-1.02m4.59 4.59l.31-.2q.53-.34 1.12-.1l.34.14q.59.25.48.88l-.06.32q-.11.63-.71.84l-.55.18q-.6.21-.86-.38l-.34-.75q-.26-.59.27-.93");
}

</style>
