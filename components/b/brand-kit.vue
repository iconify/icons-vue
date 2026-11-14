<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hwqaa7bbv"/><path class="bz1u23b0o"/><path class="c5b-psbnh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brand-kit" /></template>
<style>
.bz1u23b0o {
  d: path("M4 11V4.5a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2V13");
}

.c5b-psbnh {
  d: path("M5.75 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M12 5.5zA1.5 1.5 0 0 1 13.5 7A1.5 1.5 0 0 1 12 8.5A1.5 1.5 0 0 1 10.5 7A1.5 1.5 0 0 1 12 5.5m3.921 1.658L16 7a.839.839 0 0 1 1.5 0l.079.158A.927.927 0 0 1 16.75 8.5a.927.927 0 0 1-.829-1.342");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hwqaa7bbv {
  d: path("M2.5 13a2 2 0 0 1 2-2H9l2 2h8.5a2 2 0 0 1 2 2v4.5a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Z");
}

</style>
