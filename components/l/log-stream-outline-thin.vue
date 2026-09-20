<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6nj2fbya"/><path class="sixdm4bhp"/><path class="k62k_4bsl"/><path class="n7wfhbrgu"/><path class="cxodqhtoo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:log-stream-outline-thin" /></template>
<style>
.cxodqhtoo {
  d: path("m19 17 2 2 -2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k62k_4bsl {
  d: path("M3 13h16");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.n7wfhbrgu {
  d: path("M3 17h11");
}

.sixdm4bhp {
  d: path("M3 9h14");
}

</style>
