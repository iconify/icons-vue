<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dg92_ciox"/><path class="zno29s8sw"/><path class="s1rkwjrif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:equal-broken" /></template>
<style>
.dg92_ciox {
  d: path("M4 9H12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s1rkwjrif {
  d: path("M4 15H20");
}

.zno29s8sw {
  d: path("M16 9H20");
}

</style>
