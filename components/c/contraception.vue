<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l_difefks"/><path class="xwn-soedl"/><path class="q3f1_xb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contraception" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l_difefks {
  d: path("M4.5 6.25C5 9 8 10 12 10s7-1 7.5-3.75M12 10v5.5");
}

.q3f1_xb_c {
  d: path("M11.5 15.5c-.5 2.5 0 4-1 6m2-6c.5 2.5 0 4 1 6");
}

.xwn-soedl {
  fill: currentColor;
  d: path("M3 4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m15 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
