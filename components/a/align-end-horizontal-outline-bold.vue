<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jkuojibnm"/><path class="rtofn9dtv"/><path class="qc4g9_58r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-end-horizontal-outline-bold" /></template>
<style>
.jkuojibnm {
  d: path("M3 20h18");
}

.qc4g9_58r {
  d: path("M14 11h4v6h-4Z");
}

.rtofn9dtv {
  d: path("M7 7h4v10H7Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
