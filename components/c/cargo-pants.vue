<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kfvkns3dx"/><path class="gjohz4b-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cargo-pants" /></template>
<style>
.gjohz4b-n {
  d: path("M5 10.5h3.25v6H4.5m14.5-6h-3.25v6h3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfvkns3dx {
  d: path("M5.5 2.5h13l1.5 19h-6.25L12 10l-1.75 11.5H4Zm0 3h13");
}

</style>
