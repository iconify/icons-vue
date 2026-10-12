<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fc402mqte"/><rect class="vqagmfmyj"/><path class="jt9uy_bjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel" /></template>
<style>
.fc402mqte {
  d: path("M5.25 20.25v-15a2.5 2.5 0 0 1 2.5-2.5h4.5a2.5 2.5 0 0 1 2.5 2.5v15Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jt9uy_bjd {
  d: path("M3.75 20.25h12.5m-1.5-11h1.5a1.5 1.5 0 0 1 1.5 1.5v5.5a1.5 1.5 0 0 0 3 0V8.5L18.25 6");
}

.vqagmfmyj {
  width: 4.5px;
  height: 4px;
  x: 7.75px;
  y: 5.5px;
  rx: 0.75px;
}

</style>
