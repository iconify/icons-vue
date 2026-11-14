<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wwvx7b6tn"/><path class="zowafbbhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ahead-only-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wwvx7b6tn {
  d: path("M8 2.5h8A3.5 3.5 0 0 1 19.5 6v6a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 12V6A3.5 3.5 0 0 1 8 2.5m4 13v6m0-8.75V5.5");
}

.zowafbbhr {
  d: path("M8.75 8.75L12 5.5l3.25 3.25");
}

</style>
