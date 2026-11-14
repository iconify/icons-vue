<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vrd7as-qq"/><path class="rrteiymaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-gold-savings" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rrteiymaf {
  d: path("M4.5 10.5h-2v3h2m3.25-2.75h.01M10.5 8.5h3m.744 10.731l.644-1.75a1.5 1.5 0 0 1 1.408-.981h2.908a1.5 1.5 0 0 1 1.408.981l.644 1.75a1.5 1.5 0 0 1-1.407 2.019h-4.198a1.5 1.5 0 0 1-1.407-2.019M14.75 18h6");
}

.vrd7as-qq {
  d: path("M11.732 18c-.61-.004-1.075-.031-1.732-.25v1.75H7.5V17C5.25 16 4 14.25 4 12c0-3.5 3.5-6 8-6s8 2.5 8 6q-.001.933-.28 1.743");
}

</style>
