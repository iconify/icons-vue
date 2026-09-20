<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0n63pb2v"/><path class="xn7bwccty"/><path class="sj2zz9b3r"/><path class="dy-bj6bwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fact-store-outline-thin" /></template>
<style>
.dy-bj6bwq {
  d: path("M14 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.sj2zz9b3r {
  d: path("M8 10h4");
}

.xn7bwccty {
  d: path("M8 6h8");
}

</style>
