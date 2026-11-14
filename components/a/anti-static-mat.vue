<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aw_1417tb"/><path class="shuezlbjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anti-static-mat" /></template>
<style>
.aw_1417tb {
  d: path("M7.726 4.5h11.276a1.75 1.75 0 0 1 1.644 2.348l-2.727 7.5a1.75 1.75 0 0 1-1.645 1.152H4.998a1.75 1.75 0 0 1-1.644-2.348l2.727-7.5A1.75 1.75 0 0 1 7.726 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.shuezlbjy {
  d: path("M12 15.5c0 4 4.5 2.5 5.5 6M14 8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
