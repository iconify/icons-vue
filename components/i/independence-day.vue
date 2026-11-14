<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tpz9-jbcg"/><path class="xgtm0wqxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:independence-day" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tpz9-jbcg {
  d: path("M4.5 2.5v19m0-18c3.5-1.5 6 1.5 9 .25c2.5-1 4.5-.75 6-.25v11c-1.5-.5-3.5-.75-6 .25c-3 1.25-5.5-1.75-9-.25");
}

.xgtm0wqxr {
  d: path("m12.411 7.184l.06.134a1.5 1.5 0 0 0 1.221.887l.146.015a.45.45 0 0 1 .254.783l-.109.098a1.5 1.5 0 0 0-.467 1.435l.031.144a.45.45 0 0 1-.665.484l-.127-.074a1.5 1.5 0 0 0-1.51 0l-.127.074a.45.45 0 0 1-.665-.484l.031-.144a1.5 1.5 0 0 0-.467-1.435l-.109-.098a.45.45 0 0 1 .254-.783l.146-.015a1.5 1.5 0 0 0 1.221-.887l.06-.134a.45.45 0 0 1 .822 0");
}

</style>
