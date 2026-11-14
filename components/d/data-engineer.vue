<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nse2ubzii"/><path class="f9s638foq"/><path class="bim2vfbjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-engineer" /></template>
<style>
.bim2vfbjn {
  d: path("M14.5 14v4.75m3 2.75H22");
}

.f9s638foq {
  fill: currentColor;
  d: path("M16.375 15.25h2.254a1.5 1.5 0 0 1 1.06.439l.872.872a1.5 1.5 0 0 1 .439 1.06v1.754a1.125 1.125 0 0 1-1.125 1.125a1.125 1.125 0 0 1-1.125-1.125V19a1.5 1.5 0 0 0-1.5-1.5h-.875a1.125 1.125 0 0 1-1.125-1.125a1.125 1.125 0 0 1 1.125-1.125");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nse2ubzii {
  d: path("M12.872 21H4.5c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.331 0 .653.018M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
