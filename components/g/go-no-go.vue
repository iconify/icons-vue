<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g28-hgkxm"/><path class="zq_k0-mpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:go-no-go" /></template>
<style>
.g28-hgkxm {
  d: path("M12 2.5zA5.5 5.5 0 0 1 17.5 8v8a5.5 5.5 0 0 1-5.5 5.5A5.5 5.5 0 0 1 6.5 16V8A5.5 5.5 0 0 1 12 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zq_k0-mpn {
  d: path("M9.5 8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m0 8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
