<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zkjclebdp"/><path class="htpkuubab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-clover-four" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.htpkuubab {
  d: path("M12 17.5c0 2 .75 3 2.25 4");
}

.zkjclebdp {
  d: path("M9 7a3.25 3.25 0 1 1 6 0a3.25 3.25 0 1 1 0 6a3.25 3.25 0 1 1-6 0a3.25 3.25 0 1 1 0-6");
}

</style>
