<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="syt9yu79f"/><path class="d4p0wgucb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lane-arrow-sharp-right" /></template>
<style>
.d4p0wgucb {
  d: path("M19 11.5v5h-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.syt9yu79f {
  d: path("M7 20.5v-16l12 12");
}

</style>
