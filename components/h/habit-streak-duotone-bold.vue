<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sv5la6biz"/><path class="f51fqab3a"/><path class="cu26jmb_i"/><path class="j835zw5-z"/><path class="q7kpryb3v"/><path class="a8cyhwbdj"/><path class="ldb7pvb-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:habit-streak-duotone-bold" /></template>
<style>
.a8cyhwbdj {
  d: path("M16 2v3");
}

.cu26jmb_i {
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.f51fqab3a {
  fill: currentColor;
  d: path("M12 11c1 2.5 3 3.5 3 6a3 3 0 1 1 -6 0c0 -2 1.5 -2.5 1.5 -3.5 0.5 0.5 1.5 0.5 1.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j835zw5-z {
  d: path("M3 9h18");
}

.ldb7pvb-l {
  d: path("M12 11c1 2.5 3 3.5 3 6a3 3 0 1 1 -6 0c0 -2 1.5 -2.5 1.5 -3.5 0.5 0.5 1.5 0.5 1.5 -2.5");
}

.q7kpryb3v {
  d: path("M8 2v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sv5la6biz {
  fill: currentColor;
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
