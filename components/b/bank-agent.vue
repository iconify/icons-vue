<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wywkxlb-s"/><path class="zqjsjfbih"/><path class="n0vc39b7b"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bank-agent" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0vc39b7b {
  d: path("M11.7 20.4q-.105.14-.239.252t-.29.19t-.326.118t-.345.04H9q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076q-.062-.041-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T7.5 19.5v-4q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126q.041-.062.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049q.07-.022.142-.036q.073-.015.146-.022T9 14h1.5q.127 0 .251.021q.125.021.245.063q.119.042.23.103q.111.062.21.141t.183.173q.085.095.152.202t.115.224t.077.241M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.wywkxlb-s {
  d: path("m3 9l1.5-5h15L21 9M3 9a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0");
}

.zqjsjfbih {
  d: path("M4.5 10.5V21H12m7.5-8.8v-1.7M9 4l-.5 4.5M15 4l.5 4.5");
}

</style>
