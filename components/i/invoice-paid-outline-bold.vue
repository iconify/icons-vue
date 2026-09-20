<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nreq_9ofo"/><path class="csyuhrrop"/><path class="rt_zplbzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:invoice-paid-outline-bold" /></template>
<style>
.csyuhrrop {
  d: path("M5 14V3h14v11");
}

.nreq_9ofo {
  d: path("M2 11v10h20V11L12 21Z");
}

.rt_zplbzl {
  d: path("m9 9 2 2 4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
