<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y-rphqbye"/><path class="la_v0ub4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:frog-prince" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.la_v0ub4w {
  d: path("M8 17q4 2 8 0");
}

.y-rphqbye {
  d: path("M3 16c0-2.5.5-3.5 1-4a2.75 2.75 0 0 1 5-1.25h6A2.75 2.75 0 0 1 20 12c.5.5 1 1.5 1 4c0 3-4 5-9 5s-9-2-9-5M9.5 5.75V4.652a.426.426 0 0 1 .75-.277l.022.026A.742.742 0 0 0 11.5 4.25a.559.559 0 0 1 1 0a.742.742 0 0 0 1.228.151l.022-.026a.426.426 0 0 1 .75.277V5.75a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5m-3 6.75h.01m10.99 0h.01");
}

</style>
